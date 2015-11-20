# Tech Quiz
## A real-time web application that allows players to compete in a quiz game that test their knowlege in tech and awards points.

### Actors/Models

* Player
  * id
  * name
  * email
  * encrypted_password

* Game
  * id
  * winner_id

* Question
  * id
  * text

* Answer
  * id
  * question_id
  * text
  * correct

* PlayerAnswer
  * id
  * player_id
  * answer_id

* GameQuestion
  * id
  * game_id
  * question_id

* GamePlayer
  * id
  * game_id
  * player_id

