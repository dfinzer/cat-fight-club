# Cat Fight Club

Cat fight club is a smart contract that allows cryptokity owners to pit their cryptokitties against others in ferocious battles.

## Draft white "pawper"

### Game mechanics

Game mechanics are a work in progress. Here are a couple of preliminary ideas:

#### Points-based approach

Each kitty starts with a certain number of points. When your kitty engages in battle, it gains or loses points in a game that is a non-deterministic function of cryptokitty DNA + # of points. When your kitty dips below 0, it's sent to a graveyard address.

#### Staking approach

When two kitties want to battle, both owners stake a certain amount of ETH. The winner (again, determined by a pseudo-random function of kitty DNA) would receive all the ETH. If other parties could bet on battles too, this could evolve down more of a gambling path.

#### "Rock paper scissors" approach

Not sure if there's a more formal name for this, but the idea would be that for each fight a player could choose a particular move (for example, "scratch"). There would be a predetermined rock-paper-scissors-like interaction between each of these moves that would determine the winner (perhaps combined with a random component).