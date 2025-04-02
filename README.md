# Decapodes Syntax Highlighter Extension

This is a VSCode extension for Decapode Syntax Highlighting.

## Features

The goal of this extension is to provide proper syntax highlighting to the Decapode string macro. Initially, the Decapode DSL was supported
by a syntactic macro. This meant we were able to rely on Julia to provide proper syntax highlighting via their VSCode extension. However,
when we utilize a string macro, we are constrained to the Julia extension's quotation highlighting. This brings back Julia highlighting to
the string macro.

![Before Highlighting](https://github.com/cscaff/Decapodes-Syntax-Highlighter-Extension/blob/master/images/before.png)

![After Highlighting](https://github.com/cscaff/Decapodes-Syntax-Highlighter-Extension/blob/master/images/after.png)

## Requirements

The Julia extension should already be installed.