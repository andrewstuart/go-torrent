# Design

## Classes
- `Peer`
  - `Send chan<- FileChunk`
  - `Receive <-chan FileChunk`
- `Torrent`
  - `[]FileChunk`
  - `FindPeer() chan<- Peer`
- `Magnet`
  - `FindFile() chan<- Torrent`
