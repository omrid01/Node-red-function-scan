# Node-red-function-scan
Custom Node-red adaptation with function-scan node

## Installation Guide (macOS)

1. Install **Node.js** from https://nodejs.org/en/download.
Take the latest LTS version for macOS (v22.17.1), accept all installation defaults (NodeJS in ~/usr/local/bin/node~, npm in ~/usr/local/bin/npm~).
Once installed, verify by opening a terminal, typing **node --version** and **npm --version**, see you get valid responses.

2. Download the directory-tree `.node-red` from this repository (`omrid01/Node-red-function-scan`), to your home directory (`~`).

3. From Terminal, Go to `~/.node-red`, run Node-red with the script `start-node-red.sh` (if needed, first make it executable with `chmode +x`). See that Node-red loads properly, and says "Started flows"

4. Open Chrome, access the Node-red editor at http://localhost:1880 . It includes the `function_scan` node in the node palette (in the `function` category), and a pre-defined testing flow in the tab `Diff`.

5. You can open a UI client for testing (which uses the Node-red dashboard), at http://localhost:1880/dashboard/diff.

6. The `function_scan` node which was developed for this trial, includes detailed on-line reference which can be viewed in the Node-red editor.
