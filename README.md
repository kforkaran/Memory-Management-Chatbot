# Memory-Management-Chatbot

The ChatBot code creates a dialogue where users can ask questions about some aspects of memory management in C++. After the knowledge base of the chatbot has been loaded from a text file, a knowledge graph representation is created in computer memory, where chatbot answers represent the graph nodes and user queries represent the graph edges. After a user query has been sent to the chatbot, the Levenshtein distance is used to identify the most probable answer.

## Dependencies for Running Locally

- cmake >= 3.11
- make >= 4.1 (Linux, Mac), 3.81 (Windows)
- gcc/g++ >= 5.4
- wxWidgets >= 3.0

To install wxWidgets on Linux: `sudo apt-get install libwxgtk3.0-dev libwxgtk3.0-0v5-dbg`

## Build Instructions

- Clone this repo
- Make a build directory in the top level directory: `mkdir build && cd build`
- Compile: `cmake .. && make`
- Run: `./membot`
