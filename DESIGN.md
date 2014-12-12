# Classes
- Peer
  - Send chan&lt- FileChunk
  - Receive &lt-chan FileChunk
- File
  - []FileChunk
  - FindPeer() chan&lt- Peer
- Magnet
  - FindFile() chan&lt- File
