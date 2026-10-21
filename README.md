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
| [edukit-furuta-pendulum-rl](https://github.com/tctibbs/edukit-furuta-pendulum-rl) | Furuta pendulum, on real hardware | PPO in NVIDIA Isaac Lab, run on the board's microcontroller | Done |

In-progress projects are private until they reach a presentable state, then
get added here with links.

## Frameworks

Reusable building blocks behind the games above.

| Framework | Purpose | Used by |
|---|---|---|
| [matchbox-rl](https://github.com/tctibbs/matchbox-rl) | MENACE-style tabular RL engine for discrete games | [tic-tac-brainiac](https://github.com/tctibbs/tic-tac-brainiac) |

## Showcase

<table>
  <tr>
    <th width="39%"><a href="https://github.com/tctibbs/donkey-kong-rl">Donkey Kong</a></th>
    <th width="61%"><a href="https://github.com/tctibbs/edukit-furuta-pendulum-rl">Furuta pendulum</a></th>
  </tr>
  <tr>
    <td><img src="https://raw.githubusercontent.com/tctibbs/donkey-kong-rl/main/assets/donkey_kong_before_after.gif" width="100%" alt="Donkey Kong agent: left a plain PPO agent farms the bottom of the first screen, right the same network trained with self-imitation climbs, clears, and loops the game"></td>
    <td><img src="https://raw.githubusercontent.com/tctibbs/edukit-furuta-pendulum-rl/main/docs/experiments/07-showcase/figures/swing_up.webp" width="32%" alt="Furuta pendulum: the learned policy swinging up from rest and balancing"> <img src="https://raw.githubusercontent.com/tctibbs/edukit-furuta-pendulum-rl/main/docs/experiments/07-showcase/figures/jethro_swing_up.webp" width="32%" alt="Furuta pendulum: Jethro, a gentler fine-tune, swinging up and balancing"> <img src="https://raw.githubusercontent.com/tctibbs/edukit-furuta-pendulum-rl/main/docs/experiments/07-showcase/figures/cat_boxing.webp" width="32%" alt="Furuta pendulum: a black cat boxing the rotor arm"></td>
  </tr>
</table>

<table>
  <tr>
    <th width="22.4%"><a href="https://github.com/tctibbs/flappy-bird-rl">Flappy Bird</a></th>
    <th width="77.6%"><a href="https://github.com/tctibbs/tic-tac-brainiac">Tic-tac-toe</a></th>
  </tr>
  <tr>
    <td><img src="https://raw.githubusercontent.com/tctibbs/flappy-bird-rl/main/docs/media/demo.gif?v=2" width="100%" alt="Flappy Bird agent"></td>
    <td><img src="https://raw.githubusercontent.com/tctibbs/tic-tac-brainiac/main/assets/learning_demo.gif?v=2" width="100%" alt="Tic Tac Brainiac agent learning"></td>
  </tr>
</table>

<table>
  <tr>
    <th width="100%"><a href="https://github.com/tctibbs/neural-noodle">Snake</a></th>
  </tr>
  <tr>
    <td><img src="https://raw.githubusercontent.com/tctibbs/neural-noodle/develop/docs/demo.gif?v=1" width="100%" alt="Neural Noodle Snake agent across four board sizes"></td>
  </tr>
</table>

## License

MIT.
