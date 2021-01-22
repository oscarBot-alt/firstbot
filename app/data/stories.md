## happy path
* greet
  - utter_greet
  - utter_greet1
  - utter_greet2
  - utter_greet3
* mood_great
  - utter_happy

## sad path 1
* greet
  - utter_greet
* mood_unhappy
  - utter_cheer_up
  - utter_did_that_help
* affirm
  - utter_happy

## sad path 2
* greet
  - utter_greet
* mood_unhappy
  - utter_cheer_up
  - utter_did_that_help
* deny
  - utter_goodbye

## say goodbye
* goodbye
  - utter_goodbye
  - utter_goodbye1

## bot challenge
* bot_challenge
  - utter_iamabot

## menu path
* menu
  - utter_menu
  - utter_services
  - utter_catalog
