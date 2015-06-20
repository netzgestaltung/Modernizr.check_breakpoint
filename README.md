# Modernizr.check_breakpoint
* checks if the size of the viewport is narrower then a given number
* the check can be revertet by the second parameter(default: false)

## requires
* Modernizr.mq()

## support for respond.js
* supports oder browser when respond.js with mediaquery support is used
* requires Modernizr.mediaqueriesrespond and Modernizr.viewport() (they come bundled within)

## License
* GPLv2

## usage

    var breakpoint = 500,
        isBelowBreakpoint = Modernizr.check_breakpoint(breakpoint);
        
    if ( isBelowBreakpoint ) {
      // do stuff under 500px
    }


    var breakpoint = 500,
        isOverBreakpoint = Modernizr.check_breakpoint(breakpoint, true);
        
    if ( isOverBreakpoint ) {
      // do stuff over 500px
    }


