# BPM Process Flow More Information Settings

This module is part of the BPM perspective and serves to define a set of additional information that must be given to go from one step to the next.

This module defines a module where we will save additional information about a transition in the BPM flow. So, if we need to ask the user for some additional information when we transition from one state to another in a business process flow, this module will hold the information of

- where those fields will be saved (see the [Module BPM Information module](https://github.com/coreBOS/ModuleBPMInfo) for a template)
- what fields will be presented in the popup screen
- what field dependencies will be present
- what validation must be done in that popup form

Thus, this is a configuration module that extends the functionality of the [Process Flow Perspective](https://github.com/coreBOS/ProcessFlowPerspective). You will find some more information there.
