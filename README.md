# Tmux-Manual

## Add/delete a new session

```bash
tmux new -s [session name]
tmux kill-session -t [session name]
tmux kill-session -a
```

## Save Sessions

```bash
ctrl+a -> d # Save state and exit
```

## Continue a session

```bash
tmux attach -t [session name] # or
tmux attach
```

## Add/remove a new window

```bash
ctrl+a -> c
ctrl+d # Delete
```

## Switching Windows

```bash
ctrl+a -> [n|p]
```

## Split Window

```bash
ctrl+a -> % # horizontal
ctrl+a -> " # vertical
```

## Resizing

```bash
ctrl+a -> i # Up
ctrl+a -> k # Down
ctrl+a -> j # Left
ctrl+a -> l # Right
```

## Copy Mode

```bash
# Functions
ctrl+a -> [ # Copy mode
[v|spc]     # Select
[y|Return]  # Copy
Esc         # Cancel
q           # Exit copy mode

# Search 
/           # Search down
?           # Search up
n           # Next result
N           # Previous result

# Page
ctrl+a -> b # Page up
ctrl+a -> f # Page down
```

## Show Key-Bindings

```bash
ctrl+a -> ?
```

## Command

```bash
ctrl+a -> :
a -d   # Detach other sessions
```

## Reload tmux

```bash
ctrl+a -> r
```
