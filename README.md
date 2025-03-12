# pode README

This is a VSCode extension for Decapode Syntax Highlighting. This extension will eventually be generalized to an AlgebraicJulia Syntax Highlighter.

## Features

The goal of this extension is to provide proper syntax highlighting to the Decapode string macro. Initially, the Decapode DSL was supported
by a syntactic macro. This meant we were able to rely on Julia to provide proper syntax highlighting via their VSCode extension. However,
when we utilize a string macro, we are constrained to the Julia extension's quotation highlighting. This brings back Julia highlighting to
the string macro.

![Example](images\highlightingExample.png)

## Requirements

The VSCode Julia extension should be installed prior.

## Known Issues

Unable to change general foreground color to differentiate Decapodes block from Julia code.