# Progressive Texas Hold'em: Interactive Game Simulator

Visit https://garzon.github.io/progressiveTexasHoldem/ to play.

## 🚀 Overview

This project is a feature-rich, standalone game simulator for the casino poker variant "Progressive Texas Hold'em." Built with HTML, CSS, and JavaScript, it allows users to play the game directly in their browser against dealer.
The simulator features a user-friendly interface, multi-language support, and requires no backend or dependencies.

## 🃏 The Game: Progressive Texas Hold'em Rules

This is a Player vs. Dealer poker game with the following core rules:

* **Ante:** The player places an initial "Ante" bet.
* **The Deal:** The player and dealer each receive two private hole cards. Five community cards are eventually dealt.
* **Pre-flop Decision:** After seeing their two cards, the player must choose to:
    * **Fold:** Forfeit the Ante bet and end the hand.
    * **Play:** Make a "Flop" bet equal to 2x the Ante.
* **Post-flop Bet:** After the first three community cards (the Flop) are dealt, the player can:
    * **Check:** Make no additional bet.
    * **Bet:** Make a "Turn" bet equal to 1x the Ante.
* **Post-turn Bet:** After the fourth community card (the Turn) is dealt, the player can:
    * **Check:** Make no additional bet.
    * **Bet:** Make a "River" bet equal to 1x the Ante.
* **Showdown:** After the fifth card (the River) is dealt, hands are compared.
    * **Player Wins:** If the player's 5-card hand is better than the dealer's, all Play, Turn, and River bets are paid 1:1. The Ante bet is a push (returned).
    * **Player Loses:** The player loses all bets.
    * **Push:** If hands are identical, all bets are returned.
* **Key Rule:** The dealer **never folds** and has **no qualifying hand**. They play 100% of their random hands to the showdown.
