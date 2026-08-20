# First-time setup

Public guide: [GitHub · First-time setup](https://github.com/ConGaAI/AI-Forge/blob/main/docs/en/first-run.md)

Follow the sidebar: Connection → (optional) Data setup → Agents.  
[Status](/docs/AI-Forge/Status) tells you the next step. Connection and authorization happen in the window.

## 1. Save the username

1. Open **Connection**.
2. Enter the username your admin gave you.
3. Click **Save**.

A wrong name makes connect fail later.

## 2. Authorize this computer

![Authorize](/assets/ai-forge/authorize.png)

1. Click **Authorize**.
2. Click **Copy key** (the full line; do not select the shortened text on screen).
3. Send that line to an admin.
4. Come back after they finish.

**Done when:** the admin says this computer is allowed.

## 3. Connect and paste the service key

![Connection](/assets/ai-forge/connection.png)

Click **Connect**. Wait until the status is connected.

1. Paste the **service key** from your admin (not the authorization key).
2. Click **Save and verify**.

When it works, conversation and document understanding both show available. The key is passed into assistants you launch later.

**Unauthorized** means the admin has not allowed this computer, or you did not copy the full authorization key. **Remote unreachable** means check the network, then **Retry**.

**Done when:** the channel is up, and both conversation and document understanding are available.

## 4. Install the local store (recommended)

A prompt may appear the first time. Choose **Install**, or **Later** / **Skip**. You can still install it on [Data setup](/docs/AI-Forge/Data).

If you skip, assistants still launch, but you cannot create datasets or import files.

## 5. Launch the first assistant

Open **Agents**, pick an assistant, add a project folder, click the folder name. Details: [Agents](/docs/AI-Forge/Agents).
