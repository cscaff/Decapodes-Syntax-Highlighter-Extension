# Decapodes Syntax Highlighter Extension

This is a VSCode extension for Decapode Syntax Highlighting.

## Features

The goal of this extension is to provide proper syntax highlighting to the Decapode string macro. Initially, the Decapode DSL was supported
by a syntactic macro. This meant we were able to rely on Julia to provide proper syntax highlighting via the VSCode Julia Language Mode. However, when we utilize a string macro, we are constrained to the Julia extension's quotation highlighting. This extension brings back Julia highlighting back to the string macro.

When calling ```decapodes"..."```, Julia syntax is now embedded within the code block.

## Requirements

The Julia extension should already be installed.

The Julia language mode should be activated.