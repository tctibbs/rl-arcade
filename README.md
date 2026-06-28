# RL Arcade

An index of my reinforcement learning projects. Each game lives in its own
repository with its own agent, training pipeline, and results.

## Projects

| Project | Game | Method | Status |
|---|---|---|---|
| [flappy-bird-rl](https://github.com/tctibbs/flappy-bird-rl) | Flappy Bird | DQN (Stable-Baselines3) | Done |
| [tic-tac-brainiac](https://github.com/tctibbs/tic-tac-brainiac) | Tic-tac-toe | MENACE-style tabular learning | Done |
| [neural-noodle](https://github.com/tctibbs/neural-noodle) | Snake | PPO, scored on efficiency vs a planner oracle | Done |
| slay-the-spire-gym + slay-the-spire-rl | Slay the Spire | Maskable PPO | In progress |
| [donkey-kong-rl](https://github.com/tctibbs/donkey-kong-rl) | Donkey Kong | PPO + self-imitation learning | Done |

In-progress projects are private until they reach a presentable state, then
get added here with links.

## Frameworks

Reusable building blocks behind the games above.

| Framework | Purpose | Used by |
|---|---|---|
| [matchbox-rl](https://github.com/tctibbs/matchbox-rl) | MENACE-style tabular RL engine for discrete games | [tic-tac-brainiac](https://github.com/tctibbs/tic-tac-brainiac) |

<p align="center">
  <img src="https://raw.githubusercontent.com/tctibbs/flappy-bird-rl/main/docs/media/demo.gif?v=2" alt="Flappy Bird agent" height="280">
  &nbsp;&nbsp;
  <img src="https://raw.githubusercontent.com/tctibbs/tic-tac-brainiac/main/assets/learning_demo.gif?v=2" alt="Tic Tac Brainiac agent learning" height="280">
</p>

<p align="center">
  <img src="https://raw.githubusercontent.com/tctibbs/neural-noodle/develop/docs/demo.gif?v=1" alt="Neural Noodle Snake agent across four board sizes" width="640">
</p>

<p align="center">
  <img src="https://raw.githubusercontent.com/tctibbs/donkey-kong-rl/main/assets/donkey_kong_before_after.gif" alt="Donkey Kong agent: left a plain PPO agent farms the bottom of the first screen, right the same network trained with self-imitation climbs, clears, and loops the game" width="640">
</p>

## License

MIT.
