## Welcome to the adaptation of GPLEX for dotnet core.

Project based on [Gardens Point LEX] (https://gplex.codeplex.com/)

#### How to use
For use in dotnet core projects you need add next text in project.json

`  "tools": {
    "StarodubOleg.GPLEX": "0.1.0-alpha1-2"
  },`

`  "scripts": {
    "precompile": [ "dotnet gplex %project:Directory%/gplex.lex" ]
  }`