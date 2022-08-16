# Ssehc
* Ssehc is a chess variant with normal chess rules played in reverse.
* Moves must be made such that if the game were recorded and played backward it would appear to be a legal forward chess game with an unusual starting position.
* The goal is to end the game with your pieces in their starting positions (or as close as possible).

## **Starting a Game**
* Setup the board with each king two squares forward from their normal starting position (white king on F3, black king on F6).
* All other pieces start off the board (they are "captured") and will be "un-captured" back onto the board throughout the game.
* White starts the game by un-moving their king.

## **Taking a Turn**
* Each turn consists of two parts: maybe un-capture one of your pieces, then un-move one of your pieces.

### **Un-Capturing**
* This step is optional unless otherwise noted in "Kings" or "Pawns".
* Place one of your "captured" (off the board) pieces onto the board at the location from which your opponent un-moved their piece.

### **Un-Moving**
* This step is required.
* The piece you un-move does not need to be the same piece which you un-captured.
* Generally, pieces move the same way they do in normal chess, see "Kings" and "Pawns" for exceptions.

### **Kings** (are Complicated in Reverse)
* **Un-Single-Step**: A king may move one step in any direction.
* **Un-Castling**: If your king/rook are in a castled position, and there is nothing in the way and you're not un-castling into, out of, or through check, then you may un-castle (un-move both the king and rook to their starting position).
* **After Un-Castling**: Your opponent may not un-capture a piece on their next turn. You may not un-move your king or this rook for the rest of the game.
* **Check**: You may end your turn with your king in check (and announce "check") as long as it can legally be removed from check before you're next un-move.
* **Un-Check**: You may not end your turn with your opponent in check unless your oppenent can legally remove themselves from check with an un-capture. A player who starts their turn in check must un-capture out of check.

### **Pawns** (are Complicated in Reverse)
* **Un-Single-Step**: A pawn may move backward one square *preventing* your opponent from un-capturing.
* **Un-Double-Step**: A pawn on the 4th rank may move backward two squares *preventing* your opponent from un-capturing.
* **Force-Un-Capture**: Pawns can move backward at an angle one space *forcing* your opponent to un-captured a piece. Force-un-capture is only legal if your opponent can legally un-capture a pieces.
* **Un-Promoting**: Any non-king piece on your last row can be swapped by a captured pawn before you un-move (the old piece becomes captured). The pawn must be un-moved on the same turn (if it can't legally un-move, then un-promoting was not legal).
* **Un-En-passant**: If your opponent's pawn un-moved backward at an angle from your third row to your 4th row, you may un-capture a pawn on your 4th row on the file their pawn un-moved from (and announce "en-passant").
* Pawns may never be un-moved or un-captured to their first row.

## **Ending a Game**
* During the un-move phase of your turn, if all your pieces are on the board and your only legal un-moves would take a piece out of its home position then you may declare the game over. See "Scoring" to determine the winner.
* Resigning, or draw by repition, stalemate, mutual agreement, 50-move-rule, are the same as normal chess.

### **Scoring**
* The winner is the player with most pieces in their home position
* Tie break by the player with the most pieces on the board
* Tie break by the player with the lowest total sum of distances between their first row and each of their pieces.
