# Elixir Enum.each List Modification

This repository demonstrates a common issue when working with `Enum.each` in Elixir and attempting to modify the list being iterated over.  The code in `bug.exs` shows that changes made within the `Enum.each` function do not affect the original list. The correct approach, shown in `bugSolution.exs`, involves using other functions like `Enum.filter` for modifying list elements based on conditionals. 

## How to reproduce
1. Clone the repository.
2. Navigate to the directory.
3. Run `elixir bug.exs` (The solution is in `bugSolution.exs`)
