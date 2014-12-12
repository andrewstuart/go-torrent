# Design

## Classes
- `Peer`
  - `Send chan<- FileChunk`
  - `Receive <-chan FileChunk`
- `File`
  - `[]FileChunk`
  - `FindPeer() chan<- Peer`
- `Magnet`
  - `FindFile() chan<- File`
