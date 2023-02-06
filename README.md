# plotdemo
A copy of the plotsdemo Julia example from the Quarto docs.

The purpose is as an example to illustrate the use of the `freeze` execute option and whether that is enough to have the [publish action](https://github.com/quarto-dev/quarto-actions/publish) succeed without needing to configure Jupyter, Julia and IJulia.

In theory the `_freeze` directory should contain sufficient information to render the notebook without Jupyter and a Jupyter kernel.
