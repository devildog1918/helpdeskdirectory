# Department Directory

Standalone static PWA for Tech Support contacts. Upload the contents of this folder to a GitHub Pages repository and enable Pages from the root of the main branch.

Features: name/title/team search, team filters, local favorites, email links, Teams chat/call links, and group chat (select two or more).

**Teams:** Deep links launch Teams. Calls and group chats require signed-in authorized Teams accounts; behavior depends on organizational policies. Video can be selected within Teams if supported.

**Data:** contacts.json contains work contact information and is publicly accessible if hosted on public GitHub Pages. Do not publish non-public contact details without approval. Favorites are stored locally in the browser.

**Updates:** Edit contacts.json and increment CACHE in service-worker.js for reliable update rollouts.
