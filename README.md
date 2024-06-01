# yuzu Multiplayer Dedicated Lobby

Quickly stand up new dedicated multiplayer lobbies that will be broadcasted on sudachi.

## Usage

```
sudo docker run -d \
  --publish 5000:5000/udp \
  sudachi-multiplayer-dedicated \
  --room-name "TITLE" \
  --preferred-game "GAME TITLE" \
  --preferred-game-id "TITLE ID" \
  --port 5000 \
  --max_members 4 \
```
