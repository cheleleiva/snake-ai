## Reward

- eat food: +10
- game over: -10
- else:  0

## Action

- straight `[1, 0, 0]`
- right turn `[0, 1, 0]`
- left turn `[0, 0, 1]`

## State

11 variables

```
[danger straight, danger right, danger left,
direction left, direction right, direction up, direction down,
food left, food right, food up, food down]
```

### Model

Feed Forward Multi-perceptron Neural Network

- Inputs Layer: 11 Neurons (State)
- Hidden Layer: (1 layer)
- Output Layer: 3 Neurons (Actions)