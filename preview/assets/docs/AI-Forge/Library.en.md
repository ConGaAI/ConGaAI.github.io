# Library

Public guide: [GitHub · Library](https://github.com/ConGaAI/AI-Forge/blob/main/docs/en/library.md)

![Library](/assets/ai-forge/library.png)

After files are in a dataset, launched assistants can search them.

If you are not connected, the service key has not passed document-understanding checks, or the local store is not ready, the page lists the missing steps and lets you jump there.

## Create a dataset

1. Type a name, e.g. `product-docs`.
2. Click **Add**.

Size comes from the document-understanding service on the channel. There is no field to edit. If the service behind the key changes later, create a new dataset.

## Import files

1. Pick the **target dataset**.
2. Click **Choose files**.
3. Click **Start import**.

The stages are roughly: parse → understand → write. You can pick several files at once. If one file fails, others may still succeed.

## Using it with an assistant

No extra setup after import. Launch an assistant from [Agents](/docs/AI-Forge/Agents) and ask in ordinary language.
