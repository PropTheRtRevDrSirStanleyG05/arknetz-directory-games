# arknetz-directory-games

ArkNetzWebWeaver directory shard for category `games` (MIT). One repo per
category (REPO-TOPOLOGY.md §8): a viral category cannot bloat the whole
directory, and clients download only the categories they search.

- `directory-games.json.zst` — canonical file (live empty state: `{"cards":[]}`,
  35 bytes). `directory-games.json` is the plain mirror.
- Search metadata cards are ~150 bytes each (PROTOCOL.md §3.6).

Live state: no sites listed in this category yet — an empty directory is
the live starting state, not test data.
