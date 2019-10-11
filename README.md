// expands first and second
<Accordion dataArray={dataArray} expanded={[0, 1]} expandMultiple />

// still valid, will expand one item at a time
<Accordion dataArray={dataArray} expanded={0} />

// also valid, will expand the first item
// expanded property will be used in a state array internally
<Accordion dataArray={dataArray} expanded={0} expandMultiple/>

// its valid you guessed it :)
// but will expand second item only
<Accordion dataArray={dataArray} expanded={[1,2]} />
