# Chess Board

## Features
- Define a ChessBoard class
  - should have `add_red` method that accepts a row and column as input
  - should have `add_blue` method that accepts a row and column as input
  - should have `render` method that displays the chess board on screen with red and blue shown in correct locations
  - should have `is_under_attack` method that return boolean if red is under attack by a blue piece horizontally, vertically or diagonally

## Acceptance Tests
- queens on same row should be “under attack”
- queens on same column should be “under attack”
- queens on same diagonal should be “under attack”
- queens with any other coordinates should NOT be “under attack”

## Pull Request
[PR #1](https://github.com/eugenemonnier/chess_board/pull/1)