### Custom Linux make Build Automation Engine

A robust, minimal custom implementation of the standard Linux build utility (make) engineered from scratch in C. This tool parses target files, maps dependency relationships, evaluates modifications dynamically using file timestamps, and controls modular system compilation workflows. 

### 🚀 Key Features

* **Dynamic Token Parsing**: Streams individual structural rule inputs cleanly, applying memory block operations (memmove) to clean up whitespaces and system tabs automatically.
* **Timestamp Evaluation**: Inspects underlying file architectures using standard stat arrays to check epoch tracking metrics (st_mtime), guaranteeing that only outdated code chunks invoke rebuilding sequences.
* **Dynamic Collection Management**: Employs scalable vector tracking arrays using systematic heap allocations (realloc) to track build priorities on the fly.
* **Automated Task Invocation**: Translates explicit compilation sequences safely into target environments by verifying file paths before invoking build mechanisms.
* **Structural Integrity Enforcement**: Detects source anomalies early (e.g., target missing its matching source file) and halts execution trees instantly using graceful exits to protect files from corrupted states.

### ⚙️ How it Works under the Hood

1. **Rule Acquisition**: Reads tracking scripts chunk by chunk via custom string collectors to isolate target tags, dependencies, and shell recipes.
2. **State Verification**: Compares the modification time configurations of an object file (.o) against its base dependency (.c). If the system finds a modified source, the compilation sequence unlocks.
3. **Execution Sequencing**: Gathers all out-of-date assets into tracking arrays, firing translation workflows chronologically to produce verified executable bundles.

### 🛠️ Compilation & Execution

Compile the source files using any native standard C compiler: 

bash

# Compile the custom tool
gcc make.c -o my_make

# Run it directly inside directories containing a compliant build configuration file
./my_make

Use code with caution.

### 🧰 Tech Stack & Core APIs Used

* **Language**: Pure C
* **System Structures**: sys/stat.h, sys/types.h, unistd.h, stdio.h
* **Concepts**: Low-level String Tokenizing, Epoll-style Time Evaluation, Memory Allocation management, Automated Compilation Pipelines
