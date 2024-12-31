# tma
## tmux Attach


Select and attach to any existing tmux session with a minimum of fuss.  

### Modes of Operation
1. With no arguments:
 - If only one active session exists, it will attach to it.
 - If multiple active sessions exist, an interactive selecion menu will be presented.

2. With optional session name argument:
  - If presented with session name, simply attach to it.

3. With optional create option:
  - If presented with create option, create a new session with (optional) desired name, otherwise, a random session name will be assigned.

## Usage
    tma [-c] [tmux-session-name]
    Attach to a session: tma [tmux-session-name]
    Create a new session: tma -c [tmux-session-name]

## [Releases](https://github.com/jnyilas/tma/releases)
