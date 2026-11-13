# Hexbreak

A cybersecurity roguelike that runs in the browser. You are on call at 02:14 and something is already inside the network.

**Play:** https://eddyarriaga00.github.io/hexbreak/

Each run is three sectors of short security challenges and a boss at the end of each. Win to score and build a combo; mistakes push the breach meter toward 100%. Spend credits on upgrades between sectors. Everything you get wrong is explained, and every concept you meet is saved to your codex.

## The challenges

| Challenge | What it teaches |
|---|---|
| Phish Tank | Spotting phishing: lookalike domains, link mismatches, reply-to fraud, the @ trick |
| Packet Gate | Firewall rules, first-match ordering, CIDR ranges |
| Onion Decoder | Base64, hex, binary, URL, ASCII, ROT13, Atbash and Caesar layers |
| Log Hunt | SQL injection, XSS, path traversal, SSRF, Log4Shell, brute force and more in web logs |
| Bit Flip | Binary, hex, ASCII, bitwise operators, two's complement, subnet masks |
| Leaky Lock | Side channels and how each guess shrinks the search space |
| Quarantine | Network containment and minimum cuts in a graph |
| Crack Order | Password strength, entropy and dictionary attacks |
| Bisect | Binary search, as in `git bisect` |
| Port Knock | Well-known ports and services |
| Rapid Recall | 116 questions on security and computer science fundamentals |

There is also a daily run with a rule twist, a Blitz survival mode, practice drills, five operators, five bosses, achievements and ranks.

## Running it

It is a single `index.html` with no build step and no dependencies. Open it in a browser, or serve the folder with any static server. Progress is saved in the browser's local storage.

All companies, people and addresses in the game are fictional.
