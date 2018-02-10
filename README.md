# Offloading Server
Server for handling computation offloading requests.

## Granularity
Supporting offloading at method-level

## Data Exchange
Object serializable

## Applications

### ChestWalk
Source: https://gitlab.com/chesswalk/chesswalk

Offloading method:
```ruby
int getBestMove(char *fen, int depth, int moveTime);
```
