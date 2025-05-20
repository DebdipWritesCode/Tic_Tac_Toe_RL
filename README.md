# 🧠 Tic Tac Toe with Reinforcement Learning and MiniMax

This project implements a Tic Tac Toe game using two intelligent agents:

* A **Reinforcement Learning (RL)** agent trained via PPO.
* An agent based on the **MiniMax algorithm** with memoization for optimization.

It showcases how AI can learn and optimize decision-making in classic games using two powerful paradigms: model-free RL and adversarial search.

---

## 📂 Project Structure

| File                      | Description                                                                                                |
| ------------------------- | ---------------------------------------------------------------------------------------------------------- |
| `tictactoe_rl.ipynb`      | Implements PPO for training and simulating RL agents playing against each other.                    |
| `tictactoe_minimax.ipynb` | Implements the MiniMax algorithm with memoization to play optimally against the RL agent or human players. |

---

## 🎮 Features

* ✅ RL vs RL gameplay: two agents learn optimal strategies via self-play.
* ✅ RL agent trained using Q-learning with ε-greedy policy.
* ✅ MiniMax agent with pruning and memoization for speed.
* ✅ Visual and tabular result tracking (wins, losses, draws).
* ✅ Interactive step-by-step gameplay in Jupyter Notebook.

---

## 📊 Technologies Used

* Python
* Jupyter Notebook
* NumPy
* Matplotlib (for visualization, if used)

---

## 🧠 Reinforcement Learning Approach

* **Q-learning** with state-action mapping (`Q-table`).
* Exploration-exploitation tradeoff using ε-greedy strategy.
* Reward structure:

  * Win: +1
  * Draw: 0
  * Loss: -1
* Agent learns through **self-play** and iterative Q-table updates.

---

## ♟️ MiniMax Algorithm

* Deterministic and adversarial decision-making.
* Explores all possible moves and counter-moves.
* Memoization to avoid redundant recalculations.
* Always plays the optimal move.

---

## ✅ Results Summary

| Matchup            | Outcome                                                      |
| ------------------ | ------------------------------------------------------------ |
| RL vs RL           | Agents converge to near-optimal strategy over episodes.      |
| RL vs MiniMax      | MiniMax usually wins unless RL has enough training episodes. |
| MiniMax vs MiniMax | Always ends in a draw due to perfect play.                   |

---

## 📌 Future Improvements

* Add GUI using `pygame` or `tkinter`.
* Incorporate Deep Q-Network (DQN) for larger boards.
* Add human vs AI interactive mode.

