SublimeMockery
==============

SublimeMockery adds support for [Mockery](https://github.com/padraic/mockery) to Sublime Text 2 and 3.


Usage
-----

SublimeMockery contains snippets, most of which can be invoked with `m` and the first letters of each word in the method
name. For example, `msr` is expanded to `shouldReceive(✎)`. You can also invoke multiple method calls with one `⇥`. For,
example `msroar` is expanded to `shouldReceive(✎)->once()->andReturn(✎);`. All snippets in this package are shown
below.


Snippets
--------

- `usem⇥` → `use \Mockery as m;`
- `mm⇥` → `m::mock(✎);`
- `mc⇥` → `m::close();`
- `msr⇥` → `shouldReceive(✎)`
- `mw⇥` → `with(✎)`
- `mw0⇥` → `withNoArgs()`
- `mw2⇥` → `with(✎, ✎)`
- `mw3⇥` → `with(✎, ✎, ✎)`
- `mwaa⇥` → `withAnyArgs()`
- `mo⇥` → `once()`
- `mtw⇥` → `twice()`
- `mzomt⇥` → `zeroOrMoreTimes()`
- `mt⇥` → `times(✎)`
- `mal⇥` → `atLeast()`
- `mal1⇥` → `atLeast()->once()`
- `mal2⇥` → `atLeast()->twice()`
- `malt⇥` → `atLeast()->times(✎)`
- `mam⇥` → `atMost()`
- `mam1⇥` → `atMost()->once()`
- `mam2⇥` → `atMost()->twice()`
- `mamt⇥` → `atMost()->times(✎)`
- `mar⇥` → `andReturn(✎)`
- `mat⇥` → `andThrow(✎)`

### Combined Snippets

- `msrar⇥` → `shouldReceive(✎)->andReturn(✎);`
- `msrat⇥` → `shouldReceive(✎)->andThrow(✎);`
- `msroar⇥` → `shouldReceive(✎)->once()->andReturn(✎);`
- `msroat⇥` → `shouldReceive(✎)->>once()->andThrow(✎);`
- `msrtar⇥` → `shouldReceive(✎)->times(✎)->andReturn(✎);`
- `msrtat⇥` → `shouldReceive(✎)->times(✎)->andThrow(✎);`
- `msrwaaar⇥` → `shouldReceive(✎)->withAnyArgs()->andReturn(✎);`
- `msrwaaat⇥` → `shouldReceive(✎)->withAnyArgs()->andThrow(✎);`
- `msrwaao⇥` → `shouldReceive(✎)->withAnyArgs()->once()✎;`
- `msrwaaoar⇥` → `shouldReceive(✎)->withAnyArgs()->once()->andReturn(✎);`
- `msrwaaoat⇥` → `shouldReceive(✎)->withAnyArgs()->once()->andThrow(✎);`
- `msrwaat⇥` → `shouldReceive(✎)->withAnyArgs()->times(✎)✎;`
- `msrwaatar⇥` → `shouldReceive(✎)->withAnyArgs()->times(✎)->andReturn(✎);`
- `msrwaatat⇥` → `shouldReceive(✎)->withAnyArgs()->times(✎)->andThrow(✎);`
- `msrw0o⇥` → `shouldReceive(✎)->withNoArgs()->once()✎;`
- `msrw0oar⇥` → `shouldReceive(✎)->withNoArgs()->once()->andReturn(✎);`
- `msrw0oat⇥` → `shouldReceive(✎)->withNoArgs()->once()->andThrow(✎);`
- `msrw0t⇥` → `shouldReceive(✎)->withNoArgs()->times(✎)✎;`
- `msrw0tar⇥` → `shouldReceive(✎)->withNoArgs()->times(✎)->andReturn(✎);`
- `msrw0tat⇥` → `shouldReceive(✎)->withNoArgs()->times(✎)->andThrow(✎);`
- `msrwo⇥` → `shouldReceive(✎)->with(✎)->once()✎;`
- `msrwoar⇥` → `shouldReceive(✎)->with(✎)->once()->andReturn(✎);`
- `msrwoat⇥` → `shouldReceive(✎)->with(✎)->once()->andThrow(✎);`
- `msrwt⇥` → `shouldReceive(✎)->with(✎)->times(✎)✎;`
- `msrwtar⇥` → `shouldReceive(✎)->with(✎)->times(✎)->andReturn(✎);`
- `msrwtat⇥` → `shouldReceive(✎)->with(✎)->times(✎)->andThrow(✎);`


Author
------

- [Florian Eckerstorfer](http://florian.ec) ([Twitter](http://twitter.com/Florian_),
[App.net](https://alpha.app.net/florian)).


License
-------

    The MIT License (MIT)

    Copyright (c) 2013 Florian Eckerstorfer

    Permission is hereby granted, free of charge, to any person obtaining a copy
    of this software and associated documentation files (the "Software"), to deal
    in the Software without restriction, including without limitation the rights
    to use, copy, modify, merge, publish, distribute, sublicense, and/or sell
    copies of the Software, and to permit persons to whom the Software is
    furnished to do so, subject to the following conditions:

    The above copyright notice and this permission notice shall be included in
    all copies or substantial portions of the Software.

    THE SOFTWARE IS PROVIDED "AS IS", WITHOUT WARRANTY OF ANY KIND, EXPRESS OR
    IMPLIED, INCLUDING BUT NOT LIMITED TO THE WARRANTIES OF MERCHANTABILITY,
    FITNESS FOR A PARTICULAR PURPOSE AND NONINFRINGEMENT. IN NO EVENT SHALL THE
    AUTHORS OR COPYRIGHT HOLDERS BE LIABLE FOR ANY CLAIM, DAMAGES OR OTHER
    LIABILITY, WHETHER IN AN ACTION OF CONTRACT, TORT OR OTHERWISE, ARISING FROM,
    OUT OF OR IN CONNECTION WITH THE SOFTWARE OR THE USE OR OTHER DEALINGS IN
    THE SOFTWARE.