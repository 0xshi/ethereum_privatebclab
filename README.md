# Ethereum Private Blockchain Lab

## Overview

This repository documents a **hands-on lab** exploring how Ethereum works at the protocol level using a **private blockchain**. The environment was preconfigured, and the focus of this project was on **understanding and operating Ethereum nodes**, not writing application code.

---

## Procedure

* Started and ran **two Ethereum nodes** on a private network
* Created multiple **Ethereum accounts** across nodes
* Connected nodes as **peers**
* Started a **miner** and observed DAG generation
* Identified the **coinbase account** and mining rewards
* Executed and confirmed Ether transactions

---

## Transactions Performed

* **Node 1 → Node 2** (cross-node transaction)
* **Node 2 → Node 2** (between two accounts on the same node)

These transactions demonstrate that Ethereum transactions occur **between accounts**, independent of which node stores them.

---

## Tools Used

* Ethereum (geth)
* Private Ethereum network
* VirtualBox (Ubuntu VM)

