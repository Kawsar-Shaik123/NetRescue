# NetRescue — Interactive Computer Networks Laboratory

A single-page, browser-based educational simulator.

## Modules
1. **Routing algorithms:** Dijkstra and Bellman-Ford demonstrations, editable link weights, source/destination selection, and live shortest-path results.
2. **Failure and recovery:** Click links to disconnect/restore them, switch routers off, and observe route recalculation.
3. **Packet transmission:** Choose packet count, simulated packet-loss percentage and transmission speed setting; view delivery/drop results.
4. **Performance analyzer:** View router/link availability, route cost, hop count, link utilization and packet delivery ratio.

## Run
Open `index.html` directly in Chrome, Edge, or Firefox. No installation, server, or internet connection is required.

## Publish with GitHub Pages
1. Create a public GitHub repository named `NetRescue`.
2. Upload `index.html` to the repository root.
3. Open **Settings → Pages**.
4. Choose **Deploy from a branch**, branch `main`, folder `/ (root)`, then Save.
5. The published address will be `https://YOUR-USERNAME.github.io/NetRescue/`.

## Academic scope
This is a learning simulation, not a live network monitor. Routers, links, packets, loss and performance measurements are modeled in JavaScript in the browser. Link costs are abstract weights. The speed selector is included as a user-adjustable lab setting; packet delivery and loss are simulated.
