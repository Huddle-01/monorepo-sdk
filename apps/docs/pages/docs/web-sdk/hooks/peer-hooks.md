---
sidebar_position: 3
---

# Peer Hooks

## `usePeersData`

### Description

Hook to access all peer data
<br/>
<font size="4"> **Return Type : `Peers[]`** </font>

```jsx
// JavaScript | TypeScript
import { usePeersData } from "huddle01-client/hooks";

// Example
const peers = usePeersData();

```

## `usePeerCamTrack`

### Description

Hook to access the camera track of the selected peer
<br/>
<font size="4"> **Return Type : `Promise<MediaTrack>`** </font>
**Params**

| Param  | Type   | Required                            |
| ------ | ------ | ----------------------------------- |
| peerId | string | <font color="red">`required`</font> |

```jsx
// JavaScript | TypeScript
import { usePeerCamTrack } from "huddle01-client/hooks";

// Example
const peerId = "replace-with-peer-id";
const peerCam = usePeerCamTrack(peerId);

```

## `usePeerMicTrack`

### Description

Hook to access the mic track of the selected peer

<font size="4"> **Return Type : `Promise<MediaTrack>`** </font>

**Params**

| Param  | Type   | Required                            |
| ------ | ------ | ----------------------------------- |
| peerId | string | <font color="red">`required`</font> |

```jsx
// JavaScript | TypeScript
import { usePeerMicTrack } from "huddle01-client/hooks";

// Example
const peerId = "replace-with-peer-id";
const myMic = usePeerMicTrack(peerId);

```

## `usePeerShareTrack`

### Description

Hook to access the screen share video track of the selected peer

<font size="4"> **Return Type : `Promise<MediaTrack>`** </font>

**Params**

| Param  | Type   | Required                            |
| ------ | ------ | ----------------------------------- |
| peerId | string | <font color="red">`required`</font> |

```jsx
// JavaScript | TypeScript
import { usePeerShareTrack } from "huddle01-client/hooks";

// Example
const peerId = "replace-with-peer-id";
const shareVideoTrack = usePeerShareTrack(peerId);

```

## `usePeerShareAudioTrack`

### Description

Hook to access the screen share audio track of the selected peer

<font size="4"> **Return Type : `Promise<MediaTrack>`** </font>

**Params**

| Param  | Type   | Required                            |
| ------ | ------ | ----------------------------------- |
| peerId | string | <font color="red">`required`</font> |

```jsx
// JavaScript | TypeScript
import { usePeerShareAudioTrack } from "huddle01-client/hooks";

// Example
const peerId = "replace-with-peer-id";
const shareAudioTrack = usePeerShareAudioTrack(peerId);

```

💡 For any help reach out to us on
[Discord](https://discord.com/invite/EYqfS32jYc)
