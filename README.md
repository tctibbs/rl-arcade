# RL Arcade

An index of my reinforcement learning projects. Each game lives in its own
repository with its own agent, training pipeline, and results.

## Projects

| Project | Game | Method | Status |
|---|---|---|---|
| [flappy-bird-rl](https://github.com/tctibbs/flappy-bird-rl) | Flappy Bird | DQN (Stable-Baselines3) | Done |
| [matchbox-rl](https://github.com/tctibbs/matchbox-rl) | Tic-tac-toe and other discrete games | MENACE-style tabular learning | Done |
| slay-the-spire-gym + slay-the-spire-rl | Slay the Spire | Maskable PPO | In progress |
| donkey-kong-rl | Donkey Kong | TBD | In progress |

In-progress projects are private until they reach a presentable state, then
get added here with links.

<p align="center">
  <img src="https://raw.githubusercontent.com/tctibbs/flappy-bird-rl/main/docs/media/demo.gif" alt="Flappy Bird agent" height="280">
  &nbsp;&nbsp;
  <img src="https://raw.githubusercontent.com/tctibbs/matchbox-rl/main/assets/menace_tictactoe.png" alt="Matchbox tic-tac-toe" height="280">
</p>

## Common ground

The projects share a few habits rather than a framework:

- Results come from fixed evaluation protocols over multiple seeds, with
  mean and spread reported, never a single run.
- Configuration is typed and hashed, so any result traces back to the exact
  settings and commit that produced it.
- Training runs headless; rendering and video are separate concerns.

## License

MIT.
