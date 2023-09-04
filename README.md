# async-ws-py
A Python websocket-helper library for asynchronous handling of communication and control functionality

## Idea:
The idea for this library is to be able to do the following:
- asynchronously send and receive messages from the websocket connection
- automatically track states and messages, allowing for external functions to hook into the processing for user-functionality
- a "safe" way to interact with websocket data without locking the entire system
- being able to see DIRECTLY as well as more advanced forms of what exactly gets sent and gets received
- should be relatively easy to use (without unecessery overhead) - preferably, setting up and using should take a handfull of functions only...

furthermore, the following requirements for the usage of this library should be implemented:
1. There should be plenty of example code-snippits for implementation streamlining
2. There should be a straight forward- no black-magic method of interfacing with this library
3. the multi-threading should be structured in a sane and threadsafe way to prevent system-takeovers due to unhandled or unfinishing threads

## Collaboration:
Collaboration is welcome, please bare with me as I *slowly* write bit by bit during after-work hours...

