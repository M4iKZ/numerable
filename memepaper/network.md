# Network Spec Tech: MEMECHAIN Style

**Welcome to NUMERABLE network!** A wild, interconnected, onion-powered extravaganza that takes networking to the next level of madness.

## The Founders' Nodes (FN): The OGs of the Network
- **15 Founders' Nodes** serve as the seeds of the network. They are the legendary keepers of the memechain.
  - Each FN gets an airdrop of **500M tokens** because why not?
  - These nodes are fully interconnected in a glorious web of meme energy.
- **Mandatory Full Archive:** FN must archive the entire chain for the sake of history.

## The Other Nodes: Joining the MEME reVolution
- Other nodes can link to a **few Founders' Nodes** and participate in the network.
- Archiving is **optional**, but if not archiving, nodes will store only **30 days** of chain data.
- **User Connections:**
  - Users connect only to this last layer of nodes.
  - This ensures a streamlined experience, delivering only data relevant to their accounts.

## Gossip Protocol: Because Sharing is Caring
- We use **Gossip Protocol over WebSockets (WS)** to:
  - Accelerate the sharing of transactions while waiting for block validation.
  - Ensure everyone is in the loop with minimum fuss and maximum memes.
- Why WS over P2P? Because:
  - **Simplicity:** WS is like the "plug-and-play" of protocols.
  - **Speed:** No complex setups or connection delays.
  - **Stability:** It’s a streamlined highway for data, not a chaotic jungle of connections.

## Block Validation: MEMECHAIN Justice
- Transactions are confirmed by **every node** by verifying the data. But blocks? That’s where it gets spicy:
  - **Validators:** 
    - Nodes locking their accounts can participate as validators.
    - Validators confirm and sign blocks, with their signatures stored within the block itself.

| **Number of Nodes** | **Validators Required** |
|---------------------|-------------------------|
| Up to 50           | 5                       |
| 100                | 15                      |
| 1000               | 50                      |
| 10,000+            | 100                     |

- **Locked Accounts:**
  - Nodes must lock their accounts to participate as validators.
  - All rewards (aka memes) come from keeping the chain secure.

## Onion Protocol: Layers of Meme Perfection
- The network is structured like a perfect onion:
  1. **First Layer (Founders' Nodes):** Fully interconnected.
  2. **Middle Layer (Other Nodes):** Limited in-and-out connections.
  3. **Outer Layer (Users):** Connect to **1-2 nodes** for account-specific data.

## Storage: On-Chain Brilliance
- All scripts, code, and data are stored **on-chain** and rebuilt locally by nodes in a **db-like system**.
- Non-archiving nodes hold **30 days** of chain data. For older history, they can **ask archivers** for it.

## Future Possibilities
- Sharing **E2E encrypted data** over the chain? That’s a yes, please.
- **Other Tokens:** Maybe someday, other tokens could bring fees to the memechain. But for now, **free transactions rule** because memes should be for everyone.

---

**Disclaimer:** The MemeChain network is here to make you smile, scratch your head, and question reality. It’s built for fun and entertainment—no expectations of value or guarantees included.