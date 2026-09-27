PÉŘOVÁ ARÉNA ONLINE — serverový balíček

Toto je prototyp online 1v1 s automatickým párováním dvou připojených hráčů přes WebSocket.

LOKÁLNÍ TEST:
1. Nainstaluj Node.js 18+
2. V této složce spusť: npm install
3. Spusť: npm start
4. Otevři http://localhost:3000 ve dvou různých oknech/prohlížečích (nebo na dvou zařízeních ve stejné síti přes IP počítače).

VEŘEJNÉ ONLINE HRANÍ:
Je nutné nasadit celý projekt na server podporující Node.js a WebSocket (např. Render, Railway nebo vlastní VPS) a použít HTTPS/WSS. Statický hosting s pouhým nahráním HTML nestačí.

Poznámka: herní simulace je prototypová a klientská; pro produkční soutěžní hru je třeba přesunout fyziku a ověřování zásahů na server.
