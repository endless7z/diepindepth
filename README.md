# **:DiepInDepth**

Largest and most accurate collection of information on the browser game [diep.io](https://diep.io/).

What started off as an attempt to parse game leaderboards out of packets is now a collection of information about the insides of diep.io. Including information such as packet encoding/decoding, packet protocol, memory structures, physics, wasm parsing, game code reversal, physics, and much more.

### **Sections**

There are 4 sections that divide up the information collected.

1. Game Protocol ([`protocol/`](./protocol/))  
   Including incoming and outgoing packets, encoding/decoding, m28 server list api and websocket connections
2. WebAssembly Reversal ([`wasm/`](./wasm/))  
   Including any means necessary, asm.js conversion, specific functions, automation of reversing constants and pointers, understanding of emscripten
3. Memory Management ([`memory/`](./memory/))  
   Including storage of entities, tanks, the gui, and the structure and way things are stored
4. Extras ([`extras/`](./extras/))  
   Including any extra information, fun facts, misc algorithms, and any physics not provided in [Spade Squad](http://spade-squad.com)

## **Roadmap**

One check completes every 1-4 days.

- [ ] Complete incoming packets
- [ ] Complete outgoing packets
- [ ] Complete packet encoding stuff
- [ ] Complete rest of protocol
- [ ] Start memory and wasm
- [ ] Complete reversal of wasm code (lots of stuff here)
- [ ] Add some constants into `extras/`
- [ ] Complete all memory structs and vectors, and link up to reversal in wasm
- [ ] Double check
- [ ] Release
*wow thats a lot lol*

## **Contributors**

This repository was made possible with the help of the Diep In Depth team. In order of join date, thank you to [ABC](https://github.com/ABCxFF), [ALPH2H](https://github.com/ALPH2H), [Excigma](https://github.com/Excigma), [HueHanaejistla](https://github.com/HueHanaejistla), [Diep7444](https://github.com/diepiodiscord), [Cazka](https://github.com/Cazka), [shlong](https://github.com/shlongisdookielol), [Pola](https://github.com/PiotrDabkowski), [Binary](https://github.com/binary-person), [Perunahamsteri](https://github.com/Perunahamsteri), [Shädam](https://github.com/supahero1), and [CX](https://github.com/CX88) for their work.
