## Synopsis

Library provides hardware independent decoding procedure for RC6 remote signal.

Application has to provide HAL for library, including:
 - free running timer with frequency 1MHz and at least 16-bit resolution
 - state of pin that hardware receiver is connected. Signal on pin must have carrier signal filtered.
 - signal when input pin has changed state.

Library can be used on any platform. Tested on AVR.

## Installation

Include header to your project. Add .c file
Call RC6DecoderCreate function to create decoder object and get reference to it. 
Provide pointers to functions described in documentation. You are ready to go.

## API Reference

Almost complete API Reference can be found here: http://www.elektrofanklub.pl//doxygen/rc6.html

## License

Standard MIT License

Copyright (c) 2018 £ukasz Trojanowski

Permission is hereby granted, free of charge, to any person obtaining a copy of this software and associated documentation files (the "Software"), to deal in the Software without restriction, including without limitation the rights to use, copy, modify, merge, publish, distribute, sublicense, and/or sell copies of the Software, and to permit persons to whom the Software is furnished to do so, subject to the following conditions:

The above copyright notice and this permission notice shall be included in all copies or substantial portions of the Software.

THE SOFTWARE IS PROVIDED "AS IS", WITHOUT WARRANTY OF ANY KIND, EXPRESS OR IMPLIED, INCLUDING BUT NOT LIMITED TO THE WARRANTIES OF MERCHANTABILITY, FITNESS FOR A PARTICULAR PURPOSE AND NONINFRINGEMENT. IN NO EVENT SHALL THE AUTHORS OR COPYRIGHT HOLDERS BE LIABLE FOR ANY CLAIM, DAMAGES OR OTHER LIABILITY, WHETHER IN AN ACTION OF CONTRACT, TORT OR OTHERWISE, ARISING FROM, OUT OF OR IN CONNECTION WITH THE SOFTWARE OR THE USE OR OTHER DEALINGS IN THE SOFTWARE.