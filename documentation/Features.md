## RustDT

### Features:

 * Rust source code editor, with:
   * Syntax highlighting (configurable). 
   * Automatic indent/de-indent and brace completion on certain keypresses (Enter, Backspace).
 * Rust/Cargo Project wizard.
 * Rust/Cargo project builder.
   * With in-editor build errors reporting.

| [![sample_basic](screenshots/sample_basic.thumb.png)](screenshots/sample_basic.png?raw=true)<br/>`Editor and workbench screenshot` |
|----|

 * Content Assist and Find Definition using Racer.
 * Content Assist code snippets (configurable).

| [![sample_basic](screenshots/Feature_ContentAssist.thumb.png)](screenshots/Feature_ContentAssist.png?raw=true)<br/>`Content Assist screenshot` |
|----| 
   
##### Debugging functionality. 
Fully featured GDB debugger support (uses Eclipse CDT's GDB integration)
  * Stop/resume program execution. Listing program threads and stack frame contents.
  * Setting breakpoints, watchpoints (breakpoint on data/variables), tracepoints. Breakpoint conditions.
  * Stack variables inspection view. Expression watch and view. Disassembly view.
  * Non-stop mode (for supported GBDs). Reverse debugging (for supported GDB targets).

| [![sample_debug1](screenshots/sample_debug.thumb.png)](screenshots/sample_debug.png?raw=true)<br/>`Execution stopped on a conditional breakpoint` |
|----|
   
