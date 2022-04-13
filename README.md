# documentation
Documentation and architecture diagrams for iskprinter.com.

## Purpose

IskPrinter.com is intended to help players of the Eve Online MMO to make money (Interstellar Credits, ISK) in the game. It currently only supports station trading (buying and selling items within a single station), but future plans include system, region, and cluster trading, as well as reprocessing and manufacturing.

## Design

The architecture is divided into two parts: infrastructure and application. Some infrastructure components are deployed only in the cloud, while others are deployed both in the cloud and in the local cluster during development.

![architecture](./architecture.svg)
