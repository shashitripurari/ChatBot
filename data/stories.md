##  Story 
* goodbye
    - utter_goodbye
	- action_restart
##  Story 
* deny
    - utter_no_email_sent
	- action_restart

## interactive_story_1
* greet
    - utter_greet
* restaurant_search
    - utter_ask_location
* restaurant_search{"location": "delhi"}
    - slot{"location": "delhi"}
    - action_check_location
    - slot{"location_match": "one"}
    - utter_ask_cuisine
* restaurant_search{"cuisine": "chinese"}
    - slot{"cuisine": "chinese"}
    - utter_ask_budget
* restaurant_search{"budget": "399"}
    - slot{"budget": "399"}
    - utter_searching
    - action_restaurant
    - slot{"location": "delhi"}
    - utter_ask_for_email_to_send
* affirm
    - utter_ask_email_address
* send_email{"email": "shashit95@gmail.com"}
    - slot{"email": "shashit95@gmail.com"}
    - action_send_email
    - utter_email_sent
	- action_restart

## interactive_story_1
* greet
    - utter_greet
* restaurant_search
    - utter_ask_location
* restaurant_search{"location": "kanpur"}
    - slot{"location": "kanpur"}
    - action_check_location
    - slot{"location_match": "one"}
    - utter_ask_cuisine
* restaurant_search{"cuisine": "chinese"}
    - slot{"cuisine": "chinese"}
    - utter_ask_budget
* restaurant_search{"budget": "399"}
    - slot{"budget": "399"}
    - utter_searching
    - action_restaurant
    - slot{"location": "kanpur"}
    - utter_ask_for_email_to_send
* affirm
    - utter_ask_email_address
* send_email{"email": "shashit95@gmail.com"}
    - slot{"email": "shashit95@gmail.com"}
    - action_send_email
    - utter_email_sent
	- action_restart

## interactive_story_1
* greet
    - utter_greet
* restaurant_search
    - utter_ask_location
* restaurant_search{"location": "jaipur"}
    - slot{"location": "jaipur"}
    - action_check_location
    - slot{"location_match": "one"}
    - utter_ask_cuisine
* restaurant_search{"cuisine": "chinese"}
    - slot{"cuisine": "chinese"}
    - utter_ask_budget
* restaurant_search{"budget": "399"}
    - slot{"budget": "399"}
    - utter_searching
    - action_restaurant
    - slot{"location": "jaipur"}
    - utter_ask_for_email_to_send
* affirm
    - utter_ask_email_address
* send_email{"email": "shashit95@gmail.com"}
    - slot{"email": "shashit95@gmail.com"}
    - action_send_email
    - utter_email_sent
	- action_restart

## interactive_story_1
* greet
    - utter_greet
* restaurant_search
    - utter_ask_location
* restaurant_search{"location": "delhi"}
    - slot{"location": "delhi"}
    - action_check_location
    - slot{"location_match": "one"}
    - utter_ask_cuisine
* restaurant_search{"cuisine": "italian"}
    - slot{"cuisine": "italian"}
    - utter_ask_budget
* restaurant_search{"budget": "399"}
    - slot{"budget": "399"}
    - utter_searching
    - action_restaurant
    - slot{"location": "delhi"}
    - utter_ask_for_email_to_send
* affirm
    - utter_ask_email_address
* send_email{"email": "shashit95@gmail.com"}
    - slot{"email": "shashit95@gmail.com"}
    - action_send_email
    - utter_email_sent
	- action_restart

## interactive_story_1
* greet
    - utter_greet
* restaurant_search
    - utter_ask_location
* restaurant_search{"location": "delhi"}
    - slot{"location": "delhi"}
    - action_check_location
    - slot{"location_match": "one"}
    - utter_ask_cuisine
* restaurant_search{"cuisine": "thai"}
    - slot{"cuisine": "thai"}
    - utter_ask_budget
* restaurant_search{"budget": "399"}
    - slot{"budget": "399"}
    - utter_searching
    - action_restaurant
    - slot{"location": "delhi"}
    - utter_ask_for_email_to_send
* affirm
    - utter_ask_email_address
* send_email{"email": "shashit95@gmail.com"}
    - slot{"email": "shashit95@gmail.com"}
    - action_send_email
    - utter_email_sent
	- action_restart

## interactive_story_1
* greet
    - utter_greet
* restaurant_search
    - utter_ask_location
* restaurant_search{"location": "delhi"}
    - slot{"location": "delhi"}
    - action_check_location
    - slot{"location_match": "one"}
    - utter_ask_cuisine
* restaurant_search{"cuisine": "north indian"}
    - slot{"cuisine": "north indian"}
    - utter_ask_budget
* restaurant_search{"budget": "399"}
    - slot{"budget": "399"}
    - utter_searching
    - action_restaurant
    - slot{"location": "delhi"}
    - utter_ask_for_email_to_send
* affirm
    - utter_ask_email_address
* send_email{"email": "shashit95@gmail.com"}
    - slot{"email": "shashit95@gmail.com"}
    - action_send_email
    - utter_email_sent
	- action_restart

## interactive_story_1
* greet
    - utter_greet
* restaurant_search
    - utter_ask_location
* restaurant_search{"location": "delhi"}
    - slot{"location": "delhi"}
    - action_check_location
    - slot{"location_match": "one"}
    - utter_ask_cuisine
* restaurant_search{"cuisine": "chinese"}
    - slot{"cuisine": "chinese"}
    - utter_ask_budget
* restaurant_search{"budget": "399"}
    - slot{"budget": "399"}
    - utter_searching
    - action_restaurant
    - slot{"location": "delhi"}
    - utter_ask_for_email_to_send
* affirm
    - utter_ask_email_address
* deny
    - utter_no_email_sent
	- action_restart

## interactive_story_1
* greet
    - utter_greet
* restaurant_search
    - utter_ask_location
* restaurant_search{"location": "delhi"}
    - slot{"location": "delhi"}
    - action_check_location
    - slot{"location_match": "one"}
    - utter_ask_cuisine
* restaurant_search{"cuisine": "chinese"}
    - slot{"cuisine": "chinese"}
    - utter_ask_budget
* restaurant_search{"budget": "399"}
    - slot{"budget": "399"}
    - utter_searching
    - action_restaurant
    - slot{"location": "delhi"}
    - utter_ask_for_email_to_send
* affirm
    - utter_ask_email_address
* deny
    - utter_no_email_sent
	- action_restart

## interactive_story_1
* greet
    - utter_greet
* restaurant_search
    - utter_ask_location
* restaurant_search{"location": "delhi"}
    - slot{"location": "delhi"}
    - action_check_location
    - slot{"location_match": "one"}
    - utter_ask_cuisine
* restaurant_search{"cuisine": "chinese"}
    - slot{"cuisine": "chinese"}
    - utter_ask_budget
* restaurant_search{"budget": "399"}
    - slot{"budget": "399"}
    - utter_searching
    - action_restaurant
    - slot{"location": "delhi"}
    - utter_ask_for_email_to_send
* affirm
    - utter_ask_email_address
* deny
    - utter_no_email_sent
	- action_restart

## interactive_story_1
* greet
    - utter_greet
* restaurant_search
    - utter_ask_location
* restaurant_search{"location": "delhi"}
    - slot{"location": "delhi"}
    - action_check_location
    - slot{"location_match": "one"}
    - utter_ask_cuisine
* restaurant_search{"cuisine": "chinese"}
    - slot{"cuisine": "chinese"}
    - utter_ask_budget
* restaurant_search{"budget": "399"}
    - slot{"budget": "399"}
    - utter_searching
    - action_restaurant
    - slot{"location": "delhi"}
    - utter_ask_for_email_to_send
* affirm
    - utter_ask_email_address
* deny
    - utter_no_email_sent
	- action_restart

## interactive_story_1
* greet
    - utter_greet
* restaurant_search
    - utter_ask_location
* restaurant_search{"location": "delhi"}
    - slot{"location": "delhi"}
    - action_check_location
    - slot{"location_match": "one"}
    - utter_ask_cuisine
* restaurant_search{"cuisine": "chinese"}
    - slot{"cuisine": "chinese"}
    - utter_ask_budget
* restaurant_search{"budget": "399"}
    - slot{"budget": "399"}
    - utter_searching
    - action_restaurant
    - slot{"location": "delhi"}
    - utter_ask_for_email_to_send
* affirm
    - utter_ask_email_address
* deny
    - utter_no_email_sent
	- action_restart

## interactive_story_1
* greet
    - utter_greet
* restaurant_search
    - utter_ask_location
* restaurant_search{"location": "delhi"}
    - slot{"location": "delhi"}
    - action_check_location
    - slot{"location_match": "one"}
    - utter_ask_cuisine
* restaurant_search{"cuisine": "chinese"}
    - slot{"cuisine": "chinese"}
    - utter_ask_budget
* restaurant_search{"budget": "399"}
    - slot{"budget": "399"}
    - utter_searching
    - action_restaurant
    - slot{"location": "delhi"}
    - utter_ask_for_email_to_send
* affirm
    - utter_ask_email_address
* deny
    - utter_no_email_sent
	- action_restart

## interactive_story_1
* greet
    - utter_greet
* restaurant_search
    - utter_ask_location
* restaurant_search{"location": "delhi"}
    - slot{"location": "delhi"}
    - action_check_location
    - slot{"location_match": "one"}
    - utter_ask_cuisine
* restaurant_search{"cuisine": "chinese"}
    - slot{"cuisine": "chinese"}
    - utter_ask_budget
* restaurant_search{"budget": "399"}
    - slot{"budget": "399"}
    - utter_searching
    - action_restaurant
    - slot{"location": "delhi"}
    - utter_ask_for_email_to_send
* affirm
    - utter_ask_email_address
* deny
    - utter_no_email_sent
	- action_restart

## interactive_story_1
* greet
    - utter_greet
* restaurant_search
    - utter_ask_location
* restaurant_search{"location": "delhi"}
    - slot{"location": "delhi"}
    - action_check_location
    - slot{"location_match": "one"}
    - utter_ask_cuisine
* restaurant_search{"cuisine": "chinese"}
    - slot{"cuisine": "chinese"}
    - utter_ask_budget
* restaurant_search{"budget": "399"}
    - slot{"budget": "399"}
    - utter_searching
    - action_restaurant
    - slot{"location": "delhi"}
    - utter_ask_for_email_to_send
* deny
    - utter_no_email_sent
	- action_restart

## interactive_story_1
* greet
    - utter_greet
* restaurant_search
    - utter_ask_location
* restaurant_search{"location": "delhi"}
    - slot{"location": "delhi"}
    - action_check_location
    - slot{"location_match": "one"}
    - utter_ask_cuisine
* restaurant_search{"cuisine": "chinese"}
    - slot{"cuisine": "chinese"}
    - utter_ask_budget
* restaurant_search{"budget": "399"}
    - slot{"budget": "399"}
    - utter_searching
    - action_restaurant
    - slot{"location": "delhi"}
    - utter_ask_for_email_to_send
* deny
    - utter_no_email_sent
	- action_restart

## interactive_story_1
* greet
    - utter_greet
* restaurant_search
    - utter_ask_location
* restaurant_search{"location": "delhi"}
    - slot{"location": "delhi"}
    - action_check_location
    - slot{"location_match": "one"}
    - utter_ask_cuisine
* restaurant_search{"cuisine": "chinese"}
    - slot{"cuisine": "chinese"}
    - utter_ask_budget
* restaurant_search{"budget": "399"}
    - slot{"budget": "399"}
    - utter_searching
    - action_restaurant
    - slot{"location": "delhi"}
    - utter_ask_for_email_to_send
* deny
    - utter_no_email_sent
	- action_restart

## interactive_story_1
* greet
    - utter_greet
* restaurant_search
    - utter_ask_location
* restaurant_search{"location": "delhi"}
    - slot{"location": "delhi"}
    - action_check_location
    - slot{"location_match": "one"}
    - utter_ask_cuisine
* restaurant_search{"cuisine": "chinese"}
    - slot{"cuisine": "chinese"}
    - utter_ask_budget
* restaurant_search{"budget": "399"}
    - slot{"budget": "399"}
    - utter_searching
    - action_restaurant
    - slot{"location": "delhi"}
    - utter_ask_for_email_to_send
* deny
    - utter_no_email_sent
	- action_restart

## interactive_story_1
* greet
    - utter_greet
* restaurant_search
    - utter_ask_location
* restaurant_search{"location": "delhi"}
    - slot{"location": "delhi"}
    - action_check_location
    - slot{"location_match": "one"}
    - utter_ask_cuisine
* restaurant_search{"cuisine": "chinese"}
    - slot{"cuisine": "chinese"}
    - utter_ask_budget
* restaurant_search{"budget": "399"}
    - slot{"budget": "399"}
    - utter_searching
    - action_restaurant
    - slot{"location": "delhi"}
    - utter_ask_for_email_to_send
* deny
    - utter_no_email_sent
	- action_restart

## interactive_story_1
* greet
    - utter_greet
* restaurant_search
    - utter_ask_location
* restaurant_search{"location": "delhi"}
    - slot{"location": "delhi"}
    - action_check_location
    - slot{"location_match": "one"}
    - utter_ask_cuisine
* restaurant_search{"cuisine": "chinese"}
    - slot{"cuisine": "chinese"}
    - utter_ask_budget
* restaurant_search{"budget": "399"}
    - slot{"budget": "399"}
    - utter_searching
    - action_restaurant
    - slot{"location": "delhi"}
    - utter_ask_for_email_to_send
* deny
    - utter_no_email_sent
	- action_restart

## interactive_story_1
* greet
    - utter_greet
* restaurant_search
    - utter_ask_location
* restaurant_search{"location": "delhi"}
    - slot{"location": "delhi"}
    - action_check_location
    - slot{"location_match": "one"}
    - utter_ask_cuisine
* restaurant_search{"cuisine": "chinese"}
    - slot{"cuisine": "chinese"}
    - utter_ask_budget
* restaurant_search{"budget": "399"}
    - slot{"budget": "399"}
    - utter_searching
    - action_restaurant
    - slot{"location": "delhi"}
    - utter_ask_for_email_to_send
* deny
    - utter_no_email_sent
	- action_restart

## interactive_story_1
* greet
    - utter_greet
* restaurant_search
    - utter_ask_location
* restaurant_search{"location": "delhi"}
    - slot{"location": "delhi"}
    - action_check_location
    - slot{"location_match": "one"}
    - utter_ask_cuisine
* restaurant_search{"cuisine": "chinese"}
    - slot{"cuisine": "chinese"}
    - utter_ask_budget
* restaurant_search{"budget": "399"}
    - slot{"budget": "399"}
    - utter_searching
    - action_restaurant
    - slot{"location": "delhi"}
    - utter_ask_for_email_to_send
* deny
    - utter_no_email_sent
	- action_restart

## interactive_story_1
* greet
    - utter_greet
* restaurant_search
    - utter_ask_location
* restaurant_search{"location": "delhi"}
    - slot{"location": "delhi"}
    - action_check_location
    - slot{"location_match": "one"}
    - utter_ask_cuisine
* restaurant_search{"cuisine": "chinese"}
    - slot{"cuisine": "chinese"}
    - utter_ask_budget
* restaurant_search{"budget": "399"}
    - slot{"budget": "399"}
    - utter_searching
    - action_restaurant
    - slot{"location": "delhi"}
    - utter_ask_for_email_to_send
* deny
    - utter_no_email_sent
	- action_restart

## interactive_story_1
* greet
    - utter_greet
* restaurant_search
    - utter_ask_location
* restaurant_search{"location": "delhi"}
    - slot{"location": "delhi"}
    - action_check_location
    - slot{"location_match": "one"}
    - utter_ask_cuisine
* restaurant_search{"cuisine": "chinese"}
    - slot{"cuisine": "chinese"}
    - utter_ask_budget
* restaurant_search{"budget": "399"}
    - slot{"budget": "399"}
    - utter_searching
    - action_restaurant
    - slot{"location": "delhi"}
    - utter_ask_for_email_to_send
* deny
    - utter_no_email_sent
	- action_restart


## interactive_story_1
* greet
    - utter_greet
* restaurant_search{"location": "delhi"}
    - slot{"location": "delhi"}
    - action_check_location
    - slot{"location_match": "one"}
    - utter_ask_cuisine
* restaurant_search{"cuisine": "chinese"}
    - slot{"cuisine": "chinese"}
    - utter_ask_budget
* restaurant_search{"budget": "399"}
    - slot{"budget": "399"}
    - utter_searching
    - action_restaurant
    - slot{"location": "delhi"}
    - utter_ask_for_email_to_send
* affirm
    - utter_ask_email_address
* send_email{"email": "shashit95@gmail.com"}
    - slot{"email": "shashit95@gmail.com"}
    - action_send_email
    - utter_email_sent
	- action_restart

## interactive_story_1
* greet
    - utter_greet
* restaurant_search{"location": "Bangalore"}
    - slot{"location": "Bangalore"}
     - action_check_location
    - slot{"location_match": "one"}
    - utter_ask_cuisine
* restaurant_search{"cuisine": "chinese"}
    - slot{"cuisine": "chinese"}
    - utter_ask_budget
* restaurant_search{"budget": "399"}
    - slot{"budget": "399"}
    - utter_searching
    - action_restaurant
    - slot{"location": "Bangalore"}
    - utter_ask_for_email_to_send
* affirm
    - utter_ask_email_address
* send_email{"email": "uyhbkjn@gasf.com"}
    - slot{"email": "uyhbkjn@gasf.com"}
    - action_send_email
    - utter_email_sent
	- action_restart

## interactive_story_1
* greet
    - utter_greet
* restaurant_search{"location": "Amritsar"}
    - slot{"location": "Amritsar"}
    - action_check_location
    - slot{"location_match": "one"}
    - utter_ask_cuisine
* restaurant_search{"cuisine": "chinese"}
    - slot{"cuisine": "chinese"}
    - utter_ask_budget
* restaurant_search{"budget": "399"}
    - slot{"budget": "399"}
    - utter_searching
    - action_restaurant
    - slot{"location": "Amritsar"}
    - utter_ask_for_email_to_send
* affirm
    - utter_ask_email_address
* send_email{"email": "ayushi.dreambig@gmail.com"}
    - slot{"email": "ayushi.dreambig@gmail.com"}
    - action_send_email
    - utter_email_sent
	- action_restart

## interactive_story_1
* greet
    - utter_greet
* restaurant_search{"location": "delhi"}
    - slot{"location": "delhi"}
    - action_check_location
    - slot{"location_match": "one"}
    - utter_ask_cuisine
* restaurant_search{"cuisine": "chinese"}
    - slot{"cuisine": "chinese"}
    - utter_ask_budget
* restaurant_search{"budget": "399"}
    - slot{"budget": "399"}
    - utter_searching
    - action_restaurant
    - slot{"location": "delhi"}
    - utter_ask_for_email_to_send
* affirm
    - utter_ask_email_address
* send_email{"email": "shashit95@gmail.com"}
    - slot{"email": "shashit95@gmail.com"}
    - action_send_email
    - utter_email_sent
	- action_restart

## interactive_story_1
* greet
    - utter_greet
* restaurant_search{"location": "Nagpur"}
    - slot{"location": "Nagpur"}
    - action_check_location
    - slot{"location_match": "one"}
    - utter_ask_cuisine
* restaurant_search{"cuisine": "thai"}
    - slot{"cuisine": "thai"}
    - utter_ask_budget
* restaurant_search{"budget": "399"}
    - slot{"budget": "399"}
    - utter_searching
    - action_restaurant
    - slot{"location": "Nagpur"}
    - utter_ask_for_email_to_send
* affirm
    - utter_ask_email_address
* send_email{"email": "shashit95@gmail.com"}
    - slot{"email": "shashit95@gmail.com"}
    - action_send_email
    - utter_email_sent
	- action_restart

## interactive_story_1
* greet
    - utter_greet
* restaurant_search{"location": "delhi"}
    - slot{"location": "delhi"}
    - action_check_location
    - slot{"location_match": "one"}
    - utter_ask_cuisine
* restaurant_search{"cuisine": "chinese"}
    - slot{"cuisine": "chinese"}
    - utter_ask_budget
* restaurant_search{"budget": "699"}
    - slot{"budget": "699"}
    - utter_searching
    - action_restaurant
    - slot{"location": "delhi"}
    - utter_ask_for_email_to_send
* affirm
    - utter_ask_email_address
* send_email{"email": "shashit95@gmail.com"}
    - slot{"email": "shashit95@gmail.com"}
    - action_send_email
    - utter_email_sent
	- action_restart

## interactive_story_1
* greet
    - utter_greet
* restaurant_search{"location": "delhi"}
    - slot{"location": "delhi"}
    - action_check_location
    - slot{"location_match": "one"}
    - utter_ask_cuisine
* restaurant_search{"cuisine": "chinese"}
    - slot{"cuisine": "chinese"}
    - utter_ask_budget
* restaurant_search{"budget": "701"}
    - slot{"budget": "701"}
    - utter_searching
    - action_restaurant
    - slot{"location": "delhi"}
    - utter_ask_for_email_to_send
* affirm
    - utter_ask_email_address
* send_email{"email": "shashit95@gmail.com"}
    - slot{"email": "shashit95@gmail.com"}
    - action_send_email
    - utter_email_sent
	- action_restart

## interactive_story_1
* greet
    - utter_greet
* restaurant_search{"location": "delhi"}
    - slot{"location": "delhi"}
    - action_check_location
    - slot{"location_match": "one"}
    - utter_ask_cuisine
* restaurant_search{"cuisine": "chinese"}
    - slot{"cuisine": "chinese"}
    - utter_ask_budget
* restaurant_search{"budget": "399"}
    - slot{"budget": "399"}
    - utter_searching
    - action_restaurant
    - slot{"location": "delhi"}
    - utter_ask_for_email_to_send
* affirm
    - utter_ask_email_address
* send_email{"email": "shashit95@gmail.com"}
    - slot{"email": "shashit95@gmail.com"}
    - action_send_email
    - utter_email_sent
	- action_restart

## interactive_story_1
* greet
    - utter_greet
* restaurant_search{"location": "noida"}
    - slot{"location": "noida"}
    - action_check_location
    - slot{"location_match": "one"}
    - utter_ask_cuisine
* restaurant_search{"cuisine": "american"}
    - slot{"cuisine": "american"}
    - utter_ask_budget
* restaurant_search{"budget": "399"}
    - slot{"budget": "399"}
    - utter_searching
    - action_restaurant
    - slot{"location": "noida"}
    - utter_ask_for_email_to_send
* affirm
    - utter_ask_email_address
* send_email{"email": "shashit95@gmail.com"}
    - slot{"email": "shashit95@gmail.com"}
    - action_send_email
    - utter_email_sent
	- action_restart

## interactive_story_1
* greet
    - utter_greet
* restaurant_search{"location": "delhi"}
    - slot{"location": "delhi"}
    - action_check_location
    - slot{"location_match": "one"}
    - utter_ask_cuisine
* restaurant_search{"cuisine": "mexican"}
    - slot{"cuisine": "mexican"}
    - utter_ask_budget
* restaurant_search{"budget": "701"}
    - slot{"budget": "701"}
    - utter_searching
    - action_restaurant
    - slot{"location": "delhi"}
    - utter_ask_for_email_to_send
* affirm
    - utter_ask_email_address
* send_email{"email": "shashit95@gmail.com"}
    - slot{"email": "shashit95@gmail.com"}
    - action_send_email
    - utter_email_sent
	- action_restart

## interactive_story_1
* greet
    - utter_greet
* restaurant_search{"location": "Jalandhar"}
    - slot{"location": "Jalandhar"}
    - action_check_location
    - slot{"location_match": "one"}
    - utter_ask_cuisine
* restaurant_search{"cuisine": "chinese"}
    - slot{"cuisine": "chinese"}
    - utter_ask_budget
* restaurant_search{"budget": "399"}
    - slot{"budget": "399"}
    - utter_searching
    - action_restaurant
    - slot{"location": "Jalandhar"}
    - utter_ask_for_email_to_send
* affirm
    - utter_ask_email_address
* send_email{"email": "shashit95@gmail.com"}
    - slot{"email": "shashit95@gmail.com"}
    - action_send_email
    - utter_email_sent
	- action_restart

## interactive_story_1
* greet
    - utter_greet
* restaurant_search{"location": "delhi"}
    - slot{"location": "delhi"}
    - action_check_location
    - slot{"location_match": "one"}
    - utter_ask_cuisine
* restaurant_search{"cuisine": "chinese"}
    - slot{"cuisine": "chinese"}
    - utter_ask_budget
* restaurant_search{"budget": "399"}
    - slot{"budget": "399"}
    - utter_searching
    - action_restaurant
    - slot{"location": "delhi"}
    - utter_ask_for_email_to_send
* affirm
    - utter_ask_email_address
* deny
    - utter_no_email_sent
	- action_restart

## interactive_story_1
* greet
    - utter_greet
* restaurant_search{"location": "Bangalore"}
    - slot{"location": "Bangalore"}
    - action_check_location
    - slot{"location_match": "one"}
    - utter_ask_cuisine
* restaurant_search{"cuisine": "chinese"}
    - slot{"cuisine": "chinese"}
    - utter_ask_budget
* restaurant_search{"budget": "399"}
    - slot{"budget": "399"}
    - utter_searching
    - action_restaurant
    - slot{"location": "Bangalore"}
    - utter_ask_for_email_to_send
* affirm
    - utter_ask_email_address
* deny
    - utter_no_email_sent
	- action_restart

## interactive_story_1
* greet
    - utter_greet
* restaurant_search{"location": "Amritsar"}
    - slot{"location": "Amritsar"}
    - action_check_location
    - slot{"location_match": "one"}
    - utter_ask_cuisine
* restaurant_search{"cuisine": "chinese"}
    - slot{"cuisine": "chinese"}
    - utter_ask_budget
* restaurant_search{"budget": "399"}
    - slot{"budget": "399"}
    - utter_searching
    - action_restaurant
    - slot{"location": "Amritsar"}
    - utter_ask_for_email_to_send
* affirm
    - utter_ask_email_address
* deny
    - utter_no_email_sent
	- action_restart

## interactive_story_1
* greet
    - utter_greet
* restaurant_search{"location": "delhi"}
    - slot{"location": "delhi"}
    - action_check_location
    - slot{"location_match": "one"}
    - utter_ask_cuisine
* restaurant_search{"cuisine": "chinese"}
    - slot{"cuisine": "chinese"}
    - utter_ask_budget
* restaurant_search{"budget": "399"}
    - slot{"budget": "399"}
    - utter_searching
    - action_restaurant
    - slot{"location": "delhi"}
    - utter_ask_for_email_to_send
* deny
    - utter_no_email_sent
	- action_restart

## interactive_story_1
* greet
    - utter_greet
* restaurant_search{"location": "Nagpur"}
    - slot{"location": "Nagpur"}
    - action_check_location
    - slot{"location_match": "one"}
    - utter_ask_cuisine
* restaurant_search{"cuisine": "thai"}
    - slot{"cuisine": "thai"}
    - utter_ask_budget
* restaurant_search{"budget": "399"}
    - slot{"budget": "399"}
    - utter_searching
    - action_restaurant
    - slot{"location": "Nagpur"}
    - utter_ask_for_email_to_send
* deny
    - utter_no_email_sent
	- action_restart

## interactive_story_1
* greet
    - utter_greet
* restaurant_search{"location": "delhi"}
    - slot{"location": "delhi"}
    - action_check_location
    - slot{"location_match": "one"}
    - utter_ask_cuisine
* restaurant_search{"cuisine": "chinese"}
    - slot{"cuisine": "chinese"}
    - utter_ask_budget
* restaurant_search{"budget": "699"}
    - slot{"budget": "699"}
    - utter_searching
    - action_restaurant
    - slot{"location": "delhi"}
    - utter_ask_for_email_to_send
* deny
    - utter_no_email_sent
	- action_restart

## interactive_story_1
* greet
    - utter_greet
* restaurant_search{"location": "delhi"}
    - slot{"location": "delhi"}
    - action_check_location
    - slot{"location_match": "one"}
    - utter_ask_cuisine
* restaurant_search{"cuisine": "chinese"}
    - slot{"cuisine": "chinese"}
    - utter_ask_budget
* restaurant_search{"budget": "701"}
    - slot{"budget": "701"}
    - utter_searching
    - action_restaurant
    - slot{"location": "delhi"}
    - utter_ask_for_email_to_send
* deny
    - utter_no_email_sent
	- action_restart

## interactive_story_1
* greet
    - utter_greet
* restaurant_search{"location": "delhi"}
    - slot{"location": "delhi"}
    - action_check_location
    - slot{"location_match": "one"}
    - utter_ask_cuisine
* restaurant_search{"cuisine": "chinese"}
    - slot{"cuisine": "chinese"}
    - utter_ask_budget
* restaurant_search{"budget": "399"}
    - slot{"budget": "399"}
    - utter_searching
    - action_restaurant
    - slot{"location": "delhi"}
    - utter_ask_for_email_to_send
* deny
    - utter_no_email_sent
	- action_restart

## interactive_story_1
* greet
    - utter_greet
* restaurant_search{"location": "noida"}
    - slot{"location": "noida"}
    - action_check_location
    - slot{"location_match": "one"}
    - utter_ask_cuisine
* restaurant_search{"cuisine": "american"}
    - slot{"cuisine": "american"}
    - utter_ask_budget
* restaurant_search{"budget": "399"}
    - slot{"budget": "399"}
    - utter_searching
    - action_restaurant
    - slot{"location": "noida"}
    - utter_ask_for_email_to_send
* affirm
    - utter_ask_email_address
* deny
    - utter_no_email_sent
	- action_restart

## interactive_story_1
* greet
    - utter_greet
* restaurant_search{"location": "delhi"}
    - slot{"location": "delhi"}
    - action_check_location
    - slot{"location_match": "one"}
    - utter_ask_cuisine
* restaurant_search{"cuisine": "mexican"}
    - slot{"cuisine": "mexican"}
    - utter_ask_budget
* restaurant_search{"budget": "701"}
    - slot{"budget": "701"}
    - utter_searching
    - action_restaurant
    - slot{"location": "delhi"}
    - utter_ask_for_email_to_send
* deny
    - utter_no_email_sent
	- action_restart

## interactive_story_1
* greet
    - utter_greet
* restaurant_search{"location": "Jalandhar"}
    - slot{"location": "Jalandhar"}
    - action_check_location
    - slot{"location_match": "one"}
    - utter_ask_cuisine
* restaurant_search{"cuisine": "chinese"}
    - slot{"cuisine": "chinese"}
    - utter_ask_budget
* restaurant_search{"budget": "399"}
    - slot{"budget": "399"}
    - utter_searching
    - action_restaurant
    - slot{"location": "Jalandhar"}
    - utter_ask_for_email_to_send
* deny
    - utter_no_email_sent
	- action_restart

## interactive_story_1
* greet
    - utter_greet
* restaurant_search{"location": "Jalandhar"}
    - slot{"location": "Jalandhar"}
    - action_check_location
    - slot{"location_match": "one"}
    - utter_ask_cuisine
* restaurant_search{"cuisine": "chinese"}
    - slot{"cuisine": "chinese"}
    - utter_ask_budget
* restaurant_search{"budget": "399"}
    - slot{"budget": "399"}
    - utter_searching
    - action_restaurant
    - slot{"location": "Jalandhar"}
    - utter_ask_for_email_to_send
* deny
    - utter_no_email_sent
	- action_restart

## interactive_story_1
* greet
    - utter_greet
* restaurant_search{"location": "Jalandhar"}
    - slot{"location": "Jalandhar"}
    - action_check_location
    - slot{"location_match": "one"}
    - utter_ask_cuisine
* restaurant_search{"cuisine": "chinese"}
    - slot{"cuisine": "chinese"}
    - utter_ask_budget
* restaurant_search{"budget": "399"}
    - slot{"budget": "399"}
    - utter_searching
    - action_restaurant
    - slot{"location": "Jalandhar"}
    - utter_ask_for_email_to_send
* deny
    - utter_no_email_sent
	- action_restart

## interactive_story_1
* greet
    - utter_greet
* restaurant_search{"location": "noida"}
    - slot{"location": "noida"}
    - action_check_location
    - slot{"location_match": "one"}
    - utter_ask_cuisine
* restaurant_search{"cuisine": "american"}
    - slot{"cuisine": "american"}
    - utter_ask_budget
* restaurant_search{"budget": "399"}
    - slot{"budget": "399"}
    - utter_searching
    - action_restaurant
    - slot{"location": "noida"}
    - utter_ask_for_email_to_send
* affirm
    - utter_ask_email_address
* deny
    - utter_no_email_sent
	- action_restart

## interactive_story_1
* greet
    - utter_greet
* restaurant_search{"location": "noida"}
    - slot{"location": "noida"}
    - action_check_location
    - slot{"location_match": "one"}
    - utter_ask_cuisine
* restaurant_search{"cuisine": "american"}
    - slot{"cuisine": "american"}
    - utter_ask_budget
* restaurant_search{"budget": "399"}
    - slot{"budget": "399"}
    - utter_searching
    - action_restaurant
    - slot{"location": "noida"}
    - utter_ask_for_email_to_send
* affirm
    - utter_ask_email_address
* deny
    - utter_no_email_sent
	- action_restart

## interactive_story_1
* greet
    - utter_greet
* restaurant_search{"location": "noida"}
    - slot{"location": "noida"}
    - action_check_location
    - slot{"location_match": "one"}
    - utter_ask_cuisine
* restaurant_search{"cuisine": "american"}
    - slot{"cuisine": "american"}
    - utter_ask_budget
* restaurant_search{"budget": "399"}
    - slot{"budget": "399"}
    - utter_searching
    - action_restaurant
    - slot{"location": "noida"}
    - utter_ask_for_email_to_send
* affirm
    - utter_ask_email_address
* deny
    - utter_no_email_sent
	- action_restart

## interactive_story_1
* greet
    - utter_greet
* restaurant_search{"location": "noida"}
    - slot{"location": "noida"}
    - action_check_location
    - slot{"location_match": "one"}
    - utter_ask_cuisine
* restaurant_search{"cuisine": "american"}
    - slot{"cuisine": "american"}
    - utter_ask_budget
* restaurant_search{"budget": "399"}
    - slot{"budget": "399"}
    - utter_searching
    - action_restaurant
    - slot{"location": "noida"}
    - utter_ask_for_email_to_send
* affirm
    - utter_ask_email_address
* deny
    - utter_no_email_sent
	- action_restart

## interactive_story_1
* greet
    - utter_greet
* restaurant_search{"location": "noida"}
    - slot{"location": "noida"}
    - action_check_location
    - slot{"location_match": "one"}
    - utter_ask_cuisine
* restaurant_search{"cuisine": "american"}
    - slot{"cuisine": "american"}
    - utter_ask_budget
* restaurant_search{"budget": "399"}
    - slot{"budget": "399"}
    - utter_searching
    - action_restaurant
    - slot{"location": "noida"}
    - utter_ask_for_email_to_send
* affirm
    - utter_ask_email_address
* deny
    - utter_no_email_sent
	- action_restart

## interactive_story_1
* greet
    - utter_greet
* restaurant_search{"location": "noida"}
    - slot{"location": "noida"}
    - action_check_location
    - slot{"location_match": "one"}
    - utter_ask_cuisine
* restaurant_search{"cuisine": "american"}
    - slot{"cuisine": "american"}
    - utter_ask_budget
* restaurant_search{"budget": "399"}
    - slot{"budget": "399"}
    - utter_searching
    - action_restaurant
    - slot{"location": "noida"}
    - utter_ask_for_email_to_send
* affirm
    - utter_ask_email_address
* deny
    - utter_no_email_sent
	- action_restart

## interactive_story_1
* greet
    - utter_greet
* restaurant_search{"location": "Jalandhar"}
    - slot{"location": "Jalandhar"}
    - action_check_location
    - slot{"location_match": "one"}
    - utter_ask_cuisine
* restaurant_search{"cuisine": "chinese"}
    - slot{"cuisine": "chinese"}
    - utter_ask_budget
* restaurant_search{"budget": "399"}
    - slot{"budget": "399"}
    - utter_searching
    - action_restaurant
    - slot{"location": "Jalandhar"}
    - utter_ask_for_email_to_send
* deny
    - utter_no_email_sent
	- action_restart

## interactive_story_1
* greet
    - utter_greet
* restaurant_search{"location": "Jalandhar"}
    - slot{"location": "Jalandhar"}
    - action_check_location
    - slot{"location_match": "one"}
    - utter_ask_cuisine
* restaurant_search{"cuisine": "chinese"}
    - slot{"cuisine": "chinese"}
    - utter_ask_budget
* restaurant_search{"budget": "399"}
    - slot{"budget": "399"}
    - utter_searching
    - action_restaurant
    - slot{"location": "Jalandhar"}
    - utter_ask_for_email_to_send
* deny
    - utter_no_email_sent
	- action_restart

## interactive_story_1
* greet
    - utter_greet
* restaurant_search{"location": "Jalandhar"}
    - slot{"location": "Jalandhar"}
    - action_check_location
    - slot{"location_match": "one"}
    - utter_ask_cuisine
* restaurant_search{"cuisine": "chinese"}
    - slot{"cuisine": "chinese"}
    - utter_ask_budget
* restaurant_search{"budget": "399"}
    - slot{"budget": "399"}
    - utter_searching
    - action_restaurant
    - slot{"location": "Jalandhar"}
    - utter_ask_for_email_to_send
* deny
    - utter_no_email_sent
	- action_restart

## interactive_story_1
* greet
    - utter_greet
* restaurant_search{"location": "noida"}
    - slot{"location": "noida"}
    - action_check_location
    - slot{"location_match": "one"}
    - utter_ask_cuisine
* restaurant_search{"cuisine": "american"}
    - slot{"cuisine": "american"}
    - utter_ask_budget
* restaurant_search{"budget": "399"}
    - slot{"budget": "399"}
    - utter_searching
    - action_restaurant
    - slot{"location": "noida"}
    - utter_ask_for_email_to_send
* affirm
    - utter_ask_email_address
* deny
    - utter_no_email_sent
	- action_restart

## interactive_story_1
* greet
    - utter_greet
* restaurant_search{"location": "Jalandhar"}
    - slot{"location": "Jalandhar"}
    - action_check_location
    - slot{"location_match": "one"}
    - utter_ask_cuisine
* restaurant_search{"cuisine": "chinese"}
    - slot{"cuisine": "chinese"}
    - utter_ask_budget
* restaurant_search{"budget": "399"}
    - slot{"budget": "399"}
    - utter_searching
    - action_restaurant
    - slot{"location": "Jalandhar"}
    - utter_ask_for_email_to_send
* deny
    - utter_no_email_sent
	- action_restart


## interactive_story_1
* greet
    - utter_greet
* restaurant_search{"cuisine": "thai"}
    - slot{"cuisine": "thai"}
    - utter_ask_location
* restaurant_search{"location": "delhi"}
    - slot{"location": "delhi"}
    - action_check_location
    - slot{"location_match": "one"}
    - utter_ask_budget
* restaurant_search{"budget": "399"}
    - slot{"budget": "399"}
    - utter_searching
    - action_restaurant
    - slot{"location": "delhi"}
    - utter_ask_for_email_to_send
* affirm
    - utter_ask_email_address
* send_email{"email": "shashit95@gmail.com"}
    - slot{"email": "shashit95@gmail.com"}
    - action_send_email
    - utter_email_sent
	- action_restart

## interactive_story_1
* greet
    - utter_greet
* restaurant_search{"cuisine": "thai"}
    - slot{"cuisine": "thai"}
    - utter_ask_location
* restaurant_search{"location": "noida"}
    - slot{"location": "noida"}
    - action_check_location
    - slot{"location_match": "one"}
    - utter_ask_budget
* restaurant_search{"budget": "399"}
    - slot{"budget": "399"}
    - utter_searching
    - action_restaurant
    - slot{"location": "noida"}
    - utter_ask_for_email_to_send
* send_email{"email": "zjiom@gasf.co.in"}
    - slot{"email": "zjiom@gasf.co.in"}
    - action_send_email
    - utter_email_sent
	- action_restart

## interactive_story_1
* greet
    - utter_greet
* restaurant_search{"cuisine": "chinese"}
    - slot{"cuisine": "chinese"}
    - utter_ask_location
* restaurant_search{"location": "delhi"}
    - slot{"location": "delhi"}
    - action_check_location
    - slot{"location_match": "one"}
    - utter_ask_budget
* restaurant_search{"budget": "701"}
    - slot{"budget": "701"}
    - utter_searching
    - action_restaurant
    - slot{"location": "delhi"}
    - utter_ask_for_email_to_send
* send_email{"email": "asdsdad@gasf.com"}
    - slot{"email": "asdsdad@gasf.com"}
    - action_send_email
    - utter_email_sent
	- action_restart

## interactive_story_1
* greet
    - utter_greet
* restaurant_search{"cuisine": "chinese"}
    - slot{"cuisine": "chinese"}
    - utter_ask_location
* restaurant_search{"location": "Nashik"}
    - slot{"location": "Nashik"}
    - action_check_location
    - slot{"location_match": "one"}
    - utter_ask_budget
* restaurant_search{"budget": "399"}
    - slot{"budget": "399"}
    - utter_searching
    - action_restaurant
    - slot{"location": "Nashik"}
    - utter_ask_for_email_to_send
* send_email{"email": "asdsdad@gasf.com"}
    - slot{"email": "asdsdad@gasf.com"}
    - action_send_email
    - utter_email_sent
	- action_restart

## interactive_story_1
* greet
    - utter_greet
* restaurant_search{"cuisine": "mexican"}
    - slot{"cuisine": "mexican"}
    - utter_ask_location
* restaurant_search{"location": "delhi"}
    - slot{"location": "delhi"}
    - action_check_location
    - slot{"location_match": "one"}
    - utter_ask_budget
* restaurant_search{"budget": "399"}
    - slot{"budget": "399"}
    - utter_searching
    - action_restaurant
    - slot{"location": "delhi"}
    - utter_ask_for_email_to_send
* affirm
    - utter_ask_email_address
* send_email{"email": "shashit95@gmail.com"}
    - slot{"email": "shashit95@gmail.com"}
    - action_send_email
    - utter_email_sent
	- action_restart

## interactive_story_1
* greet
    - utter_greet
* restaurant_search{"cuisine": "mexican"}
    - slot{"cuisine": "mexican"}
    - utter_ask_location
* restaurant_search{"location": "delhi"}
    - slot{"location": "delhi"}
    - action_check_location
    - slot{"location_match": "one"}
    - utter_ask_budget
* restaurant_search{"budget": "699"}
    - slot{"budget": "699"}
    - utter_searching
    - action_restaurant
    - slot{"location": "delhi"}
    - utter_ask_for_email_to_send
* send_email{"email": "asdsdad@gasf.com"}
    - slot{"email": "asdsdad@gasf.com"}
    - action_send_email
    - utter_email_sent
	- action_restart

## interactive_story_1
* greet
    - utter_greet
* restaurant_search{"cuisine": "thai"}
    - slot{"cuisine": "thai"}
    - utter_ask_location
* restaurant_search{"location": "Chennai"}
    - slot{"location": "Chennai"}
    - action_check_location
    - slot{"location_match": "one"}
    - utter_ask_budget
* restaurant_search{"budget": "399"}
    - slot{"budget": "399"}
    - utter_searching
    - action_restaurant
    - slot{"location": "Chennai"}
    - utter_ask_for_email_to_send
* affirm
    - utter_ask_email_address
* send_email{"email": "shashit95@gmail.com"}
    - slot{"email": "shashit95@gmail.com"}
    - action_send_email
    - utter_email_sent
	- action_restart

## interactive_story_1
* greet
    - utter_greet
* restaurant_search{"cuisine": "american"}
    - slot{"cuisine": "american"}
    - utter_ask_location
* restaurant_search{"location": "Gwalior"}
    - slot{"location": "Gwalior"}
    - action_check_location
    - slot{"location_match": "one"}
    - utter_ask_budget
* restaurant_search{"budget": "399"}
    - slot{"budget": "399"}
    - utter_searching
    - action_restaurant
    - slot{"location": "Gwalior"}
    - utter_ask_for_email_to_send
* send_email{"email": "asdsdad@gasf.com"}
    - slot{"email": "asdsdad@gasf.com"}
    - action_send_email
    - utter_email_sent
	- action_restart

## interactive_story_1
* greet
    - utter_greet
* restaurant_search{"cuisine": "thai"}
    - slot{"cuisine": "thai"}
    - utter_ask_location
* restaurant_search{"location": "delhi"}
    - slot{"location": "delhi"}
    - action_check_location
    - slot{"location_match": "one"}
    - utter_ask_budget
* restaurant_search{"budget": "399"}
    - slot{"budget": "399"}
    - utter_searching
    - action_restaurant
    - slot{"location": "delhi"}
    - utter_ask_for_email_to_send
* affirm
    - utter_ask_email_address
* send_email{"email": "shashit95@gmail.com"}
    - slot{"email": "shashit95@gmail.com"}
    - action_send_email
    - utter_email_sent
	- action_restart

## interactive_story_1
* greet
    - utter_greet
* restaurant_search{"cuisine": "thai"}
    - slot{"cuisine": "thai"}
    - utter_ask_location
* restaurant_search{"location": "delhi"}
    - slot{"location": "delhi"}
    - action_check_location
    - slot{"location_match": "one"}
    - utter_ask_budget
* restaurant_search{"budget": "701"}
    - slot{"budget": "701"}
    - utter_searching
    - action_restaurant
    - slot{"location": "delhi"}
    - utter_ask_for_email_to_send
* affirm
    - utter_ask_email_address
* send_email{"email": "shashit95@gmail.com"}
    - slot{"email": "shashit95@gmail.com"}
    - action_send_email
    - utter_email_sent
	- action_restart

## interactive_story_1
* greet
    - utter_greet
* restaurant_search{"cuisine": "italian"}
    - slot{"cuisine": "italian"}
    - utter_ask_location
* restaurant_search{"location": "delhi"}
    - slot{"location": "delhi"}
    - action_check_location
    - slot{"location_match": "one"}
    - utter_ask_budget
* restaurant_search{"budget": "399"}
    - slot{"budget": "399"}
    - utter_searching
    - action_restaurant
    - slot{"location": "delhi"}
    - utter_ask_for_email_to_send
* affirm
    - utter_ask_email_address
* send_email{"email": "shashit95@gmail.com"}
    - slot{"email": "shashit95@gmail.com"}
    - action_send_email
    - utter_email_sent
	- action_restart

## interactive_story_1
* greet
    - utter_greet
* restaurant_search{"cuisine": "thai"}
    - slot{"cuisine": "thai"}
    - utter_ask_location
* restaurant_search{"location": "delhi"}
    - slot{"location": "delhi"}
    - action_check_location
    - slot{"location_match": "one"}
    - utter_ask_budget
* restaurant_search{"budget": "399"}
    - slot{"budget": "399"}
    - utter_searching
    - action_restaurant
    - slot{"location": "delhi"}
    - utter_ask_for_email_to_send
* send_email{"email": "asdsdad@gasf.com"}
    - slot{"email": "asdsdad@gasf.com"}
    - action_send_email
    - utter_email_sent
	- action_restart

## interactive_story_1
* greet
    - utter_greet
* restaurant_search{"cuisine": "italian"}
    - slot{"cuisine": "italian"}
    - utter_ask_location
* restaurant_search{"location": "Surat"}
    - slot{"location": "Surat"}
    - action_check_location
    - slot{"location_match": "one"}
    - utter_ask_budget
* restaurant_search{"budget": "399"}
    - slot{"budget": "399"}
    - utter_searching
    - action_restaurant
    - slot{"location": "Surat"}
    - utter_ask_for_email_to_send
* send_email{"email": "asdsdad@gasf.com"}
    - slot{"email": "asdsdad@gasf.com"}
    - action_send_email
    - utter_email_sent
	- action_restart


## interactive_story_1
* greet
    - utter_greet
* restaurant_search{"cuisine": "thai"}
    - slot{"cuisine": "thai"}
    - utter_ask_location
* restaurant_search{"location": "delhi"}
    - slot{"location": "delhi"}
    - action_check_location
    - slot{"location_match": "one"}
    - utter_ask_budget
* restaurant_search{"budget": "399"}
    - slot{"budget": "399"}
    - utter_searching
    - action_restaurant
    - slot{"location": "delhi"}
    - utter_ask_for_email_to_send
* affirm
    - utter_ask_email_address
* deny
    - utter_no_email_sent
	- action_restart

## interactive_story_1
* greet
    - utter_greet
* restaurant_search{"cuisine": "thai"}
    - slot{"cuisine": "thai"}
    - utter_ask_location
* restaurant_search{"location": "noida"}
    - slot{"location": "noida"}
    - action_check_location
    - slot{"location_match": "one"}
    - utter_ask_budget
* restaurant_search{"budget": "701"}
    - slot{"budget": "701"}
    - utter_searching
    - action_restaurant
    - slot{"location": "noida"}
    - utter_ask_for_email_to_send
* affirm
    - utter_ask_email_address
* deny
    - utter_no_email_sent
	- action_restart

## interactive_story_1
* greet
    - utter_greet
* restaurant_search{"cuisine": "chinese"}
    - slot{"cuisine": "chinese"}
    - utter_ask_location
* restaurant_search{"location": "delhi"}
    - slot{"location": "delhi"}
    - action_check_location
    - slot{"location_match": "one"}
    - utter_ask_budget
* restaurant_search{"budget": "701"}
    - slot{"budget": "701"}
    - utter_searching
    - action_restaurant
    - slot{"location": "delhi"}
    - utter_ask_for_email_to_send
* deny
    - utter_no_email_sent
	- action_restart

## interactive_story_1
* greet
    - utter_greet
* restaurant_search{"cuisine": "chinese"}
    - slot{"cuisine": "chinese"}
    - utter_ask_location
* restaurant_search{"location": "Nashik"}
    - slot{"location": "Nashik"}
    - action_check_location
    - slot{"location_match": "one"}
    - utter_ask_budget
* restaurant_search{"budget": "399"}
    - slot{"budget": "399"}
    - utter_searching
    - action_restaurant
    - slot{"location": "Nashik"}
    - utter_ask_for_email_to_send
* deny
    - utter_no_email_sent
	- action_restart

## interactive_story_1
* greet
    - utter_greet
* restaurant_search{"cuisine": "mexican"}
    - slot{"cuisine": "mexican"}
    - utter_ask_location
* restaurant_search{"location": "delhi"}
    - slot{"location": "delhi"}
    - action_check_location
    - slot{"location_match": "one"}
    - utter_ask_budget
* restaurant_search{"budget": "399"}
    - slot{"budget": "399"}
    - utter_searching
    - action_restaurant
    - slot{"location": "delhi"}
    - utter_ask_for_email_to_send
* affirm
    - utter_ask_email_address
* deny
    - utter_no_email_sent
	- action_restart

## interactive_story_1
* greet
    - utter_greet
* restaurant_search{"cuisine": "mexican"}
    - slot{"cuisine": "mexican"}
    - utter_ask_location
* restaurant_search{"location": "delhi"}
    - slot{"location": "delhi"}
    - action_check_location
    - slot{"location_match": "one"}
    - utter_ask_budget
* restaurant_search{"budget": "699"}
    - slot{"budget": "699"}
    - utter_searching
    - action_restaurant
    - slot{"location": "delhi"}
    - utter_ask_for_email_to_send
* affirm
    - utter_ask_email_address
* deny
    - utter_no_email_sent
	- action_restart

## interactive_story_1
* greet
    - utter_greet
* restaurant_search{"cuisine": "thai"}
    - slot{"cuisine": "thai"}
    - utter_ask_location
* restaurant_search{"location": "Chennai"}
    - slot{"location": "Chennai"}
    - action_check_location
    - slot{"location_match": "one"}
    - utter_ask_budget
* restaurant_search{"budget": "399"}
    - slot{"budget": "399"}
    - utter_searching
    - action_restaurant
    - slot{"location": "Chennai"}
    - utter_ask_for_email_to_send
* affirm
    - utter_ask_email_address
* deny
    - utter_no_email_sent
	- action_restart

## interactive_story_1
* greet
    - utter_greet
* restaurant_search{"cuisine": "american"}
    - slot{"cuisine": "american"}
    - utter_ask_location
* restaurant_search{"location": "Gwalior"}
    - slot{"location": "Gwalior"}
    - action_check_location
    - slot{"location_match": "one"}
    - utter_ask_budget
* restaurant_search{"budget": "399"}
    - slot{"budget": "399"}
    - utter_searching
    - action_restaurant
    - slot{"location": "Gwalior"}
    - utter_ask_for_email_to_send
* affirm
    - utter_ask_email_address
* deny
    - utter_no_email_sent
	- action_restart

## interactive_story_1
* greet
    - utter_greet
* restaurant_search{"cuisine": "thai"}
    - slot{"cuisine": "thai"}
    - utter_ask_location
* restaurant_search{"location": "delhi"}
    - slot{"location": "delhi"}
    - action_check_location
    - slot{"location_match": "one"}
    - utter_ask_budget
* restaurant_search{"budget": "399"}
    - slot{"budget": "399"}
    - utter_searching
    - action_restaurant
    - slot{"location": "delhi"}
    - utter_ask_for_email_to_send
* deny
    - utter_no_email_sent
	- action_restart

## interactive_story_1
* greet
    - utter_greet
* restaurant_search{"cuisine": "thai"}
    - slot{"cuisine": "thai"}
    - utter_ask_location
* restaurant_search{"location": "delhi"}
    - slot{"location": "delhi"}
    - action_check_location
    - slot{"location_match": "one"}
    - utter_ask_budget
* restaurant_search{"budget": "399"}
    - slot{"budget": "399"}
    - utter_searching
    - action_restaurant
    - slot{"location": "delhi"}
    - utter_ask_for_email_to_send
* affirm
    - utter_ask_email_address
* deny
    - utter_no_email_sent
	- action_restart

## interactive_story_1
* greet
    - utter_greet
* restaurant_search{"cuisine": "italian"}
    - slot{"cuisine": "italian"}
    - utter_ask_location
* restaurant_search{"location": "delhi"}
    - slot{"location": "delhi"}
    - action_check_location
    - slot{"location_match": "one"}
    - utter_ask_budget
* restaurant_search{"budget": "399"}
    - slot{"budget": "399"}
    - utter_searching
    - action_restaurant
    - slot{"location": "delhi"}
    - utter_ask_for_email_to_send
* affirm
    - utter_ask_email_address
* deny
    - utter_no_email_sent
	- action_restart

## interactive_story_1
* greet
    - utter_greet
* restaurant_search{"cuisine": "thai"}
    - slot{"cuisine": "thai"}
    - utter_ask_location
* restaurant_search{"location": "delhi"}
    - slot{"location": "delhi"}
    - action_check_location
    - slot{"location_match": "one"}
    - utter_ask_budget
* restaurant_search{"budget": "399"}
    - slot{"budget": "399"}
    - utter_searching
    - action_restaurant
    - slot{"location": "delhi"}
    - utter_ask_for_email_to_send
* deny
    - utter_no_email_sent
	- action_restart

## interactive_story_1
* greet
    - utter_greet
* restaurant_search{"cuisine": "italian"}
    - slot{"cuisine": "italian"}
    - utter_ask_location
* restaurant_search{"location": "Surat"}
    - slot{"location": "Surat"}
    - action_check_location
    - slot{"location_match": "one"}
    - utter_ask_budget
* restaurant_search{"budget": "399"}
    - slot{"budget": "399"}
    - utter_searching
    - action_restaurant
    - slot{"location": "Surat"}
    - utter_ask_for_email_to_send
* affirm
    - utter_ask_email_address
* deny
    - utter_no_email_sent
	- action_restart

## interactive_story_1
* greet
    - utter_greet
* restaurant_search{"cuisine": "italian", "location": "Chandigarh"}
    - slot{"cuisine": "italian"}
    - slot{"location": "Chandigarh"}
    - action_check_location
    - slot{"location_match": "one"}
    - utter_ask_budget
* restaurant_search{"budget": "399"}
    - slot{"budget": "399"}
    - utter_searching
    - action_restaurant
    - slot{"location": "Chandigarh"}
    - utter_ask_for_email_to_send
* affirm
    - utter_ask_email_address
* send_email{"email": "shashit95@gmail.com"}
    - slot{"email": "shashit95@gmail.com"}
    - action_send_email
    - utter_email_sent
	- action_restart

## interactive_story_1
* greet
    - utter_greet
* restaurant_search{"cuisine": "chinese", "location": "Patna"}
    - slot{"cuisine": "chinese"}
    - slot{"location": "Patna"}
    - action_check_location
    - slot{"location_match": "one"}
    - utter_ask_budget
* restaurant_search{"budget": "701"}
    - slot{"budget": "701"}
    - utter_searching
    - action_restaurant
    - slot{"location": "Patna"}
    - utter_ask_for_email_to_send
* affirm
    - utter_ask_email_address
* send_email{"email": "shashit95@gmail.com"}
    - slot{"email": "shashit95@gmail.com"}
    - action_send_email
    - utter_email_sent
	- action_restart

## interactive_story_1
* greet
    - utter_greet
* restaurant_search{"cuisine": "chinese", "location": "Patna"}
    - slot{"cuisine": "chinese"}
    - slot{"location": "Patna"}
    - action_check_location
    - slot{"location_match": "one"}
    - utter_ask_budget
* restaurant_search{"budget": "399"}
    - slot{"budget": "399"}
    - utter_searching
    - action_restaurant
    - slot{"location": "Patna"}
    - utter_ask_for_email_to_send
* send_email{"email": "shashit95@gmail.com"}
    - slot{"email": "shashit95@gmail.com"}
    - action_send_email
    - utter_email_sent
	- action_restart


## interactive_story_1
* greet
    - utter_greet
* restaurant_search{"cuisine": "chinese", "location": "Patna"}
    - slot{"cuisine": "chinese"}
    - slot{"location": "Patna"}
    - action_check_location
    - slot{"location_match": "one"}
    - utter_ask_budget
* restaurant_search{"budget": "399"}
    - slot{"budget": "399"}
    - utter_searching
    - action_restaurant
    - slot{"location": "Patna"}
    - utter_ask_for_email_to_send
* send_email{"email": "shashit95@gmail.com"}
    - slot{"email": "shashit95@gmail.com"}
    - action_send_email
    - utter_email_sent
    - action_restart

## interactive_story_1
* greet
    - utter_greet
* restaurant_search{"cuisine": "chinese", "location": "Patna"}
    - slot{"cuisine": "chinese"}
    - slot{"location": "Patna"}
    - action_check_location
    - slot{"location_match": "one"}
    - utter_ask_budget
* restaurant_search{"budget": "399"}
    - slot{"budget": "399"}
    - utter_searching
    - action_restaurant
    - slot{"location": "Patna"}
    - utter_ask_for_email_to_send
* send_email{"email": "shashit95@gmail.com"}
    - slot{"email": "shashit95@gmail.com"}
    - action_send_email
    - utter_email_sent
    - action_restart

## interactive_story_1
* greet
    - utter_greet
* restaurant_search{"cuisine": "chinese", "location": "Patna"}
    - slot{"cuisine": "chinese"}
    - slot{"location": "Patna"}
    - action_check_location
    - slot{"location_match": "one"}
    - utter_ask_budget
* restaurant_search{"budget": "399"}
    - slot{"budget": "399"}
    - utter_searching
    - action_restaurant
    - slot{"location": "Patna"}
    - utter_ask_for_email_to_send
* send_email{"email": "shashit95@gmail.com"}
    - slot{"email": "shashit95@gmail.com"}
    - action_send_email
    - utter_email_sent
    - action_restart

## interactive_story_1
* greet
    - utter_greet
* restaurant_search{"cuisine": "chinese", "location": "Patna"}
    - slot{"cuisine": "chinese"}
    - slot{"location": "Patna"}
    - action_check_location
    - slot{"location_match": "one"}
    - utter_ask_budget
* restaurant_search{"budget": "399"}
    - slot{"budget": "399"}
    - utter_searching
    - action_restaurant
    - slot{"location": "Patna"}
    - utter_ask_for_email_to_send
* send_email{"email": "shashit95@gmail.com"}
    - slot{"email": "shashit95@gmail.com"}
    - action_send_email
    - utter_email_sent
    - action_restart

## interactive_story_1
* greet
    - utter_greet
* restaurant_search{"cuisine": "chinese", "location": "Patna"}
    - slot{"cuisine": "chinese"}
    - slot{"location": "Patna"}
    - action_check_location
    - slot{"location_match": "one"}
    - utter_ask_budget
* restaurant_search{"budget": "399"}
    - slot{"budget": "399"}
    - utter_searching
    - action_restaurant
    - slot{"location": "Patna"}
    - utter_ask_for_email_to_send
* send_email{"email": "shashit95@gmail.com"}
    - slot{"email": "shashit95@gmail.com"}
    - action_send_email
    - utter_email_sent
    - action_restart

## interactive_story_1
* greet
    - utter_greet
* restaurant_search{"cuisine": "chinese", "location": "Patna"}
    - slot{"cuisine": "chinese"}
    - slot{"location": "Patna"}
    - action_check_location
    - slot{"location_match": "one"}
    - utter_ask_budget
* restaurant_search{"budget": "399"}
    - slot{"budget": "399"}
    - utter_searching
    - action_restaurant
    - slot{"location": "Patna"}
    - utter_ask_for_email_to_send
* send_email{"email": "shashit95@gmail.com"}
    - slot{"email": "shashit95@gmail.com"}
    - action_send_email
    - utter_email_sent
    - action_restart

## interactive_story_1
* greet
    - utter_greet
* restaurant_search{"cuisine": "chinese", "location": "Patna"}
    - slot{"cuisine": "chinese"}
    - slot{"location": "Patna"}
    - action_check_location
    - slot{"location_match": "one"}
    - utter_ask_budget
* restaurant_search{"budget": "399"}
    - slot{"budget": "399"}
    - utter_searching
    - action_restaurant
    - slot{"location": "Patna"}
    - utter_ask_for_email_to_send
* send_email{"email": "shashit95@gmail.com"}
    - slot{"email": "shashit95@gmail.com"}
    - action_send_email
    - utter_email_sent
    - action_restart

## interactive_story_1
* greet
    - utter_greet
* restaurant_search{"cuisine": "chinese", "location": "Patna"}
    - slot{"cuisine": "chinese"}
    - slot{"location": "Patna"}
    - action_check_location
    - slot{"location_match": "one"}
    - utter_ask_budget
* restaurant_search{"budget": "399"}
    - slot{"budget": "399"}
    - utter_searching
    - action_restaurant
    - slot{"location": "Patna"}
    - utter_ask_for_email_to_send
* send_email{"email": "shashit95@gmail.com"}
    - slot{"email": "shashit95@gmail.com"}
    - action_send_email
    - utter_email_sent
    - action_restart

## interactive_story_1
* greet
    - utter_greet
* restaurant_search{"cuisine": "chinese", "location": "Patna"}
    - slot{"cuisine": "chinese"}
    - slot{"location": "Patna"}
    - action_check_location
    - slot{"location_match": "one"}
    - utter_ask_budget
* restaurant_search{"budget": "399"}
    - slot{"budget": "399"}
    - utter_searching
    - action_restaurant
    - slot{"location": "Patna"}
    - utter_ask_for_email_to_send
* send_email{"email": "shashit95@gmail.com"}
    - slot{"email": "shashit95@gmail.com"}
    - action_send_email
    - utter_email_sent
    - action_restart


## interactive_story_1
* greet
    - utter_greet
* restaurant_search{"cuisine": "italian", "location": "Patna"}
    - slot{"cuisine": "italian"}
    - slot{"location": "Patna"}
    - action_check_location
    - slot{"location_match": "one"}
    - utter_ask_budget
* restaurant_search{"budget": "399"}
    - slot{"budget": "399"}
    - utter_searching
    - action_restaurant
    - slot{"location": "Patna"}
    - utter_ask_for_email_to_send
* send_email{"email": "shashit95@gmail.com"}
    - slot{"email": "shashit95@gmail.com"}
    - action_send_email
    - utter_email_sent
	- action_restart

## interactive_story_1
* greet
    - utter_greet
* restaurant_search{"cuisine": "chinese", "location": "Patna"}
    - slot{"cuisine": "chinese"}
    - slot{"location": "Patna"}
    - action_check_location
    - slot{"location_match": "one"}
    - utter_ask_budget
* restaurant_search{"budget": "701"}
    - slot{"budget": "701"}
    - utter_searching
    - action_restaurant
    - slot{"location": "Patna"}
    - utter_ask_for_email_to_send
* affirm
    - utter_ask_email_address
* send_email{"email": "shashit95@gmail.com"}
    - slot{"email": "shashit95@gmail.com"}
    - action_send_email
    - utter_email_sent
	- action_restart

## interactive_story_1
* greet
    - utter_greet
* restaurant_search{"cuisine": "italian", "location": "Patna"}
    - slot{"cuisine": "italian"}
    - slot{"location": "Patna"}
    - action_check_location
    - slot{"location_match": "one"}
    - utter_ask_budget
* restaurant_search{"budget": "399"}
    - slot{"budget": "399"}
    - utter_searching
    - action_restaurant
    - slot{"location": "Patna"}
    - utter_ask_for_email_to_send
* send_email{"email": "shashit95@gmail.com"}
    - slot{"email": "shashit95@gmail.com"}
    - action_send_email
    - utter_email_sent
	- action_restart

## interactive_story_1
* greet
    - utter_greet
* restaurant_search{"cuisine": "chinese", "location": "Patna"}
    - slot{"cuisine": "chinese"}
    - slot{"location": "Patna"}
    - action_check_location
    - slot{"location_match": "one"}
    - utter_ask_budget
* restaurant_search{"budget": "399"}
    - slot{"budget": "399"}
    - utter_searching
    - action_restaurant
    - slot{"location": "Patna"}
    - utter_ask_for_email_to_send
* send_email{"email": "shashit95@gmail.com"}
    - slot{"email": "shashit95@gmail.com"}
    - action_send_email
    - utter_email_sent
	- action_restart

## interactive_story_1
* greet
    - utter_greet
* restaurant_search{"cuisine": "chinese", "location": "Guwahati"}
    - slot{"cuisine": "chinese"}
    - slot{"location": "Guwahati"}
    - action_check_location
    - slot{"location_match": "one"}
    - utter_ask_budget
* restaurant_search{"budget": "399"}
    - slot{"budget": "399"}
    - utter_searching
    - action_restaurant
    - slot{"location": "Guwahati"}
    - utter_ask_for_email_to_send
* affirm
    - utter_ask_email_address
* send_email{"email": "shashit95@gmail.com"}
    - slot{"email": "shashit95@gmail.com"}
    - action_send_email
    - utter_email_sent
	- action_restart

## interactive_story_1
* greet
    - utter_greet
* restaurant_search{"cuisine": "italian", "location": "Patna"}
    - slot{"cuisine": "italian"}
    - slot{"location": "Patna"}
    - action_check_location
    - slot{"location_match": "one"}
    - utter_ask_budget
* restaurant_search{"budget": "399"}
    - slot{"budget": "399"}
    - utter_searching
    - action_restaurant
    - slot{"location": "Patna"}
    - utter_ask_for_email_to_send
* affirm
    - utter_ask_email_address
* send_email{"email": "shashit95@gmail.com"}
    - slot{"email": "shashit95@gmail.com"}
    - action_send_email
    - utter_email_sent
	- action_restart

## interactive_story_1
* greet
    - utter_greet
* restaurant_search{"cuisine": "chinese", "location": "Patna"}
    - slot{"cuisine": "chinese"}
    - slot{"location": "Patna"}
    - action_check_location
    - slot{"location_match": "one"}
    - utter_ask_budget
* restaurant_search{"budget": "399"}
    - slot{"budget": "399"}
    - utter_searching
    - action_restaurant
    - slot{"location": "Patna"}
    - utter_ask_for_email_to_send
* affirm
    - utter_ask_email_address
* send_email{"email": "shashit95@gmail.com"}
    - slot{"email": "shashit95@gmail.com"}
    - action_send_email
    - utter_email_sent
	- action_restart

## interactive_story_1
* greet
    - utter_greet
* restaurant_search{"cuisine": "italian", "location": "Patna"}
    - slot{"cuisine": "italian"}
    - slot{"location": "Patna"}
    - action_check_location
    - slot{"location_match": "one"}
    - utter_ask_budget
* restaurant_search{"budget": "701"}
    - slot{"budget": "701"}
    - utter_searching
    - action_restaurant
    - slot{"location": "Patna"}
    - utter_ask_for_email_to_send
* affirm
    - utter_ask_email_address
* send_email{"email": "shashit95@gmail.com"}
    - slot{"email": "shashit95@gmail.com"}
    - action_send_email
    - utter_email_sent
	- action_restart

## interactive_story_1
* greet
    - utter_greet
* restaurant_search{"cuisine": "chinese", "location": "Patna"}
    - slot{"cuisine": "chinese"}
    - slot{"location": "Patna"}
    - action_check_location
    - slot{"location_match": "one"}
    - utter_ask_budget
* restaurant_search{"budget": "399"}
    - slot{"budget": "399"}
    - utter_searching
    - action_restaurant
    - slot{"location": "Patna"}
    - utter_ask_for_email_to_send
* send_email{"email": "shashit95@gmail.com"}
    - slot{"email": "shashit95@gmail.com"}
    - action_send_email
    - utter_email_sent
	- action_restart

## interactive_story_1
* greet
    - utter_greet
* restaurant_search{"cuisine": "chinese", "location": "Patna"}
    - slot{"cuisine": "chinese"}
    - slot{"location": "Patna"}
    - action_check_location
    - slot{"location_match": "one"}
    - utter_ask_budget
* restaurant_search{"budget": "701"}
    - slot{"budget": "701"}
    - utter_searching
    - action_restaurant
    - slot{"location": "Patna"}
    - utter_ask_for_email_to_send
* send_email{"email": "shashit95@gmail.com"}
    - slot{"email": "shashit95@gmail.com"}
    - action_send_email
    - utter_email_sent
	- action_restart

## interactive_story_1
* greet
    - utter_greet
* restaurant_search{"cuisine": "chinese", "location": "Patna"}
    - slot{"cuisine": "chinese"}
    - slot{"location": "Patna"}
    - action_check_location
    - slot{"location_match": "one"}
    - utter_ask_budget
* restaurant_search{"budget": "399"}
    - slot{"budget": "399"}
    - utter_searching
    - action_restaurant
    - slot{"location": "Patna"}
    - utter_ask_for_email_to_send
* send_email{"email": "shashit95@gmail.com"}
    - slot{"email": "shashit95@gmail.com"}
    - action_send_email
    - utter_email_sent
	- action_restart

## interactive_story_1
* greet
    - utter_greet
* restaurant_search{"cuisine": "chinese", "location": "Patna"}
    - slot{"cuisine": "chinese"}
    - slot{"location": "Patna"}
    - action_check_location
    - slot{"location_match": "one"}
    - utter_ask_budget
* restaurant_search{"budget": "399"}
    - slot{"budget": "399"}
    - utter_searching
    - action_restaurant
    - slot{"location": "Patna"}
    - utter_ask_for_email_to_send
* affirm
    - utter_ask_email_address
* send_email{"email": "shashit95@gmail.com"}
    - slot{"email": "shashit95@gmail.com"}
    - action_send_email
    - utter_email_sent
	- action_restart

<!-- stories starting with cuisine and location restaurant_search, with complete restaurant_searchation and sent email -->


<!-- stories starting with cuisine and location restaurant_search, with complete restaurant_searchation and no sent email -->

## interactive_story_1
* greet
    - utter_greet
* restaurant_search{"cuisine": "chinese", "location": "Patna"}
    - slot{"cuisine": "chinese"}
    - slot{"location": "Patna"}
    - action_check_location
    - slot{"location_match": "one"}
    - utter_ask_budget
* restaurant_search{"budget": "399"}
    - slot{"budget": "399"}
    - utter_searching
    - action_restaurant
    - slot{"location": "Patna"}
    - utter_ask_for_email_to_send
* deny
    - utter_no_email_sent
	- action_restart

## interactive_story_1
* greet
    - utter_greet
* restaurant_search{"cuisine": "chinese", "location": "Bhopal"}
    - slot{"cuisine": "chinese"}
    - slot{"location": "Bhopal"}
    - action_check_location
    - slot{"location_match": "one"}
    - utter_ask_budget
* restaurant_search{"budget": "399"}
    - slot{"budget": "399"}
    - utter_searching
    - action_restaurant
    - slot{"location": "Bhopal"}
    - utter_ask_for_email_to_send
* affirm
    - utter_ask_email_address
* deny
    - utter_no_email_sent
	- action_restart

## interactive_story_1
* greet
    - utter_greet
* restaurant_search{"cuisine": "chinese", "location": "mumbai"}
    - slot{"cuisine": "chinese"}
    - slot{"location": "mumbai"}
    - action_check_location
    - slot{"location_match": "one"}
    - utter_ask_budget
* restaurant_search{"budget": "399"}
    - slot{"budget": "399"}
    - utter_searching
    - action_restaurant
    - slot{"location": "mumbai"}
    - utter_ask_for_email_to_send
* deny
    - utter_no_email_sent
	- action_restart


## interactive_story_1
* greet
    - utter_greet
* restaurant_search{"cuisine": "chinese", "location": "mumbai"}
    - slot{"cuisine": "chinese"}
    - slot{"location": "mumbai"}
    - action_check_location
    - slot{"location_match": "one"}
    - utter_ask_budget
* restaurant_search{"budget": "399"}
    - slot{"budget": "399"}
    - utter_searching
    - action_restaurant
    - slot{"location": "mumbai"}
    - utter_ask_for_email_to_send
* affirm
    - utter_ask_email_address
* deny
    - utter_no_email_sent
	- action_restart


## interactive_story_1
* greet
    - utter_greet
* restaurant_search{"cuisine": "chinese", "location": "Kozhikode"}
    - slot{"cuisine": "chinese"}
    - slot{"location": "Kozhikode"}
    - action_check_location
    - slot{"location_match": "one"}
    - utter_ask_budget
* restaurant_search{"budget": "399"}
    - slot{"budget": "399"}
    - utter_searching
    - action_restaurant
    - slot{"location": "Kozhikode"}
    - utter_ask_for_email_to_send
* affirm
    - utter_ask_email_address
* deny
    - utter_no_email_sent
	- action_restart


## interactive_story_1
* greet
    - utter_greet
* restaurant_search{"cuisine": "thai", "location": "mumbai"}
    - slot{"cuisine": "thai"}
    - slot{"location": "mumbai"}
    - action_check_location
    - slot{"location_match": "one"}
    - utter_ask_budget
* restaurant_search{"budget": "399"}
    - slot{"budget": "399"}
    - utter_searching
    - action_restaurant
    - slot{"location": "mumbai"}
    - utter_ask_for_email_to_send
* affirm
    - utter_ask_email_address
* deny
    - utter_no_email_sent
	- action_restart
<!-- stories starting with cuisine and location restaurant_search, with complete restaurant_searchation and no sent email -->

<!-- misc -->
### interactive_story_1
* greet
    - utter_greet
* goodbye
    - utter_goodbye
	- action_restart
	- action_restart

## interactive_story_1
* greet
    - utter_greet
* goodbye
    - utter_goodbye
	- action_restart
	- action_restart

## interactive_story_1
* greet
    - utter_greet
* goodbye
    - utter_goodbye
	- action_restart
	- action_restart

## interactive_story_1
* greet
    - utter_greet
* goodbye
    - utter_goodbye
	- action_restart
	- action_restart

## interactive_story_1
* greet
    - utter_greet
* restaurant_search
    - utter_ask_location
* goodbye
    - utter_goodbye
	- action_restart
	- action_restart

## interactive_story_1
* greet
    - utter_greet
* restaurant_search
    - utter_ask_location
* goodbye
    - utter_goodbye
	- action_restart
	- action_restart

## interactive_story_1
* greet
    - utter_greet
* restaurant_search
    - utter_ask_location
* goodbye
    - utter_goodbye
	- action_restart
	- action_restart

## interactive_story_1
* greet
    - utter_greet
* restaurant_search
    - utter_ask_location
* goodbye
    - utter_goodbye
	- action_restart
	- action_restart

## interactive_story_1
* greet
    - utter_greet
* restaurant_search
    - utter_ask_location
* goodbye
    - utter_goodbye
	- action_restart
	- action_restart


<!-- misc -->
<!-- leave in between -->


## interactive_story_1
* greet
    - utter_greet
* restaurant_search
    - utter_ask_location
* restaurant_search{"location": "delhi"}
    - slot{"location": "delhi"}
    - action_check_location
    - slot{"location_match": "one"}
    - utter_ask_cuisine
* goodbye
    - utter_goodbye
	- action_restart
	- action_restart

## interactive_story_1
* greet
    - utter_greet
* restaurant_search
    - utter_ask_location
* restaurant_search{"location": "delhi"}
    - slot{"location": "delhi"}
    - action_check_location
    - slot{"location_match": "one"}
    - utter_ask_cuisine
* goodbye
    - utter_goodbye
	- action_restart
	- action_restart

## interactive_story_1
* greet
    - utter_greet
* restaurant_search
    - utter_ask_location
* restaurant_search{"location": "delhi"}
    - slot{"location": "delhi"}
    - action_check_location
    - slot{"location_match": "one"}
    - utter_ask_cuisine
* goodbye
    - utter_goodbye
	- action_restart
	- action_restart

## interactive_story_1
* greet
    - utter_greet
* restaurant_search
    - utter_ask_location
* restaurant_search{"location": "noida"}
    - slot{"location": "noida"}
    - action_check_location
    - slot{"location_match": "one"}
    - utter_ask_cuisine
* goodbye
    - utter_goodbye
	- action_restart
	- action_restart


## interactive_story_1
* greet
    - utter_greet
* restaurant_search
    - utter_ask_location
* restaurant_search{"location": "delhi"}
    - slot{"location": "delhi"}
    - action_check_location
    - slot{"location_match": "one"}
    - utter_ask_cuisine
* restaurant_search{"cuisine": "thai"}
    - slot{"cuisine": "thai"}
    - utter_ask_budget
* restaurant_search{"budget": "399"}
    - slot{"budget": "399"}
    - utter_searching
    - action_restaurant
    - slot{"location": "delhi"}
    - utter_ask_for_email_to_send
* goodbye
    - utter_goodbye
	- action_restart

## interactive_story_1
* greet
    - utter_greet
* restaurant_search
    - utter_ask_location
* restaurant_search{"location": "delhi"}
    - slot{"location": "delhi"}
    - action_check_location
    - slot{"location_match": "one"}
    - utter_ask_cuisine
* restaurant_search{"cuisine": "thai"}
    - slot{"cuisine": "thai"}
    - utter_ask_budget
* restaurant_search{"budget": "399"}
    - slot{"budget": "399"}
    - utter_searching
    - action_restaurant
    - slot{"location": "delhi"}
    - utter_ask_for_email_to_send
* goodbye
    - utter_goodbye
	- action_restart

## interactive_story_1
* greet
    - utter_greet
* restaurant_search
    - utter_ask_location
* restaurant_search{"location": "delhi"}
    - slot{"location": "delhi"}
    - action_check_location
    - slot{"location_match": "one"}
    - utter_ask_cuisine
* restaurant_search{"cuisine": "thai"}
    - slot{"cuisine": "thai"}
    - utter_ask_budget
* restaurant_search{"budget": "399"}
    - slot{"budget": "399"}
    - utter_searching
    - action_restaurant
    - slot{"location": "delhi"}
    - utter_ask_for_email_to_send
* goodbye
    - utter_goodbye
	- action_restart

## interactive_story_1
* greet
    - utter_greet
* restaurant_search
    - utter_ask_location
* restaurant_search{"location": "delhi"}
    - slot{"location": "delhi"}
    - action_check_location
    - slot{"location_match": "one"}
    - utter_ask_cuisine
* restaurant_search{"cuisine": "american"}
    - slot{"cuisine": "american"}
    - utter_ask_budget
* restaurant_search{"budget": "399"}
    - slot{"budget": "399"}
    - utter_searching
    - action_restaurant
    - slot{"location": "delhi"}
    - utter_ask_for_email_to_send
* goodbye
    - utter_goodbye
	- action_restart

## interactive_story_1
* greet
    - utter_greet
* restaurant_search
    - utter_ask_location
* restaurant_search{"location": "delhi"}
    - slot{"location": "delhi"}
    - action_check_location
    - slot{"location_match": "one"}
    - utter_ask_cuisine
* restaurant_search{"cuisine": "mexican"}
    - slot{"cuisine": "mexican"}
    - utter_ask_budget
* restaurant_search{"budget": "399"}
    - slot{"budget": "399"}
    - utter_searching
    - action_restaurant
    - slot{"location": "delhi"}
    - utter_ask_for_email_to_send
* goodbye
    - utter_goodbye
	- action_restart

## interactive_story_1
* greet
    - utter_greet
* restaurant_search
    - utter_ask_location
* restaurant_search{"location": "delhi"}
    - slot{"location": "delhi"}
    - action_check_location
    - slot{"location_match": "one"}
    - utter_ask_cuisine
* restaurant_search{"cuisine": "thai"}
    - slot{"cuisine": "thai"}
    - utter_ask_budget
* restaurant_search{"budget": "399"}
    - slot{"budget": "399"}
    - utter_searching
    - action_restaurant
    - slot{"location": "delhi"}
    - utter_ask_for_email_to_send
* goodbye
    - utter_goodbye
	- action_restart

## interactive_story_1
* greet
    - utter_greet
* restaurant_search
    - utter_ask_location
* restaurant_search{"location": "noida"}
    - slot{"location": "noida"}
    - action_check_location
    - slot{"location_match": "one"}
    - utter_ask_cuisine
* restaurant_search{"cuisine": "italian"}
    - slot{"cuisine": "italian"}
    - utter_ask_budget
* restaurant_search{"budget": "701"}
    - slot{"budget": "701"}
    - utter_searching
    - action_restaurant
    - slot{"location": "noida"}
    - utter_ask_for_email_to_send
* goodbye
    - utter_goodbye
	- action_restart

## interactive_story_1
* greet
    - utter_greet
* restaurant_search{"cuisine": "chinese", "location": "mumbai"}
    - slot{"cuisine": "chinese"}
    - slot{"location": "mumbai"}
    - action_check_location
    - slot{"location_match": "one"}
    - utter_ask_budget
* goodbye
    - utter_goodbye
	- action_restart

## interactive_story_1
* greet
    - utter_greet
* restaurant_search{"cuisine": "thai"}
    - slot{"cuisine": "thai"}
    - utter_ask_location
* goodbye
    - utter_goodbye
	- action_restart

## interactive_story_1
* greet
    - utter_greet
* restaurant_search{"cuisine": "thai"}
    - slot{"cuisine": "thai"}
    - utter_ask_location
* restaurant_search{"location": "delhi"}
    - slot{"location": "delhi"}
    - action_check_location
    - slot{"location_match": "one"}
    - utter_ask_budget
* goodbye
    - utter_goodbye
	- action_restart

## interactive_story_1
* greet
    - utter_greet
* restaurant_search{"cuisine": "thai"}
    - slot{"cuisine": "thai"}
    - utter_ask_location
* restaurant_search{"location": "delhi"}
    - slot{"location": "delhi"}
    - action_check_location
    - slot{"location_match": "one"}
    - utter_ask_budget
* restaurant_search{"budget": "399"}
    - slot{"budget": "399"}
    - utter_searching
    - action_restaurant
    - slot{"location": "delhi"}
    - utter_ask_for_email_to_send
* goodbye
    - utter_goodbye
	- action_restart

<!-- leave in between -->




<!-- condition checkpoints -->

##interactive_story_1
* greet
    - utter_greet
* restaurant_search
    - utter_ask_location
* restaurant_search{"location": "delhsdadi"}
    - slot{"location": "delhsdadi"}
    - action_check_location
    - slot{"location_match": "zero"}
    - utter_location_not_found
* restaurant_search{"location": "delhi"}
    - slot{"location": "delhi"}
    - action_check_location
    - slot{"location_match": "one"}
    - utter_ask_cuisine
* restaurant_search{"cuisine": "chinese"}
    - slot{"cuisine": "chinese"}
    - utter_ask_budget
* restaurant_search{"budget": "399"}
    - slot{"budget": "399"}
    - utter_searching
    - action_restaurant
    - slot{"location": "delhi"}
    - utter_ask_for_email_to_send
* affirm
    - utter_ask_email_address
* send_email{"email": "shashit95@gmail.com"}
    - slot{"email": "shashit95@gmail.com"}
    - action_send_email
    - utter_email_sent
    - action_restart

##interactive_story_1
* greet
    - utter_greet
* restaurant_search
    - utter_ask_location
* restaurant_search{"location": "delhsdadi"}
    - slot{"location": "delhsdadi"}
    - action_check_location
    - slot{"location_match": "zero"}
    - utter_location_not_found
* restaurant_search{"location": "dlehi"}
    - slot{"location": "dlehi"}
    - action_check_location
    - slot{"location_match": "zero"}
    - utter_location_not_found
* restaurant_search{"location": "delhi"}
    - slot{"location": "delhi"}
    - action_check_location
    - slot{"location_match": "one"}
    - utter_ask_cuisine
* restaurant_search{"cuisine": "chinese"}
    - slot{"cuisine": "chinese"}
    - utter_ask_budget
* restaurant_search{"budget": "399"}
    - slot{"budget": "399"}
    - utter_searching
    - action_restaurant
    - slot{"location": "delhi"}
    - utter_ask_for_email_to_send
* affirm
    - utter_ask_email_address
* send_email{"email": "shashit95@gmail.com"}
    - slot{"email": "shashit95@gmail.com"}
    - action_send_email
    - utter_email_sent
    - action_restart

##interactive_story_1
* greet
    - utter_greet
* restaurant_search
    - utter_ask_location
* restaurant_search{"location": "delhsdadi"}
    - slot{"location": "delhsdadi"}
    - action_check_location
    - slot{"location_match": "zero"}
    - utter_location_not_found
* deny
    - utter_goodbye
    - action_restart

##interactive_story_1
* greet
    - utter_greet
* restaurant_search
    - utter_ask_location
* restaurant_search{"location": "delhsdadi"}
    - slot{"location": "delhsdadi"}
    - action_check_location
    - slot{"location_match": "zero"}
    - utter_location_not_found
* goodbye
    - utter_goodbye
    - action_restart


##interactive_story_1
* greet
    - utter_greet
* restaurant_search
    - utter_ask_location
* restaurant_search{"location": "delhsdadi"}
    - slot{"location": "delhsdadi"}
    - action_check_location
    - slot{"location_match": "zero"}
    - utter_location_not_found
* restaurant_search{"location": "dlehi"}
    - slot{"location": "dlehi"}
    - action_check_location
    - slot{"location_match": "zero"}
    - utter_location_not_found
* goodbye
    - utter_goodbye
    - action_restart


##interactive_story_1
* greet
    - utter_greet
* restaurant_search
    - utter_ask_location
* restaurant_search{"location": "delhsdadi"}
    - slot{"location": "delhsdadi"}
    - action_check_location
    - slot{"location_match": "zero"}
    - utter_location_not_found
* restaurant_search{"location": "dlehi"}
    - slot{"location": "dlehi"}
    - action_check_location
    - slot{"location_match": "zero"}
    - utter_location_not_found
* deny
    - utter_goodbye
    - action_restart


## interactive_story_1
* greet
    - utter_greet
* restaurant_search{"location": "Bangalorety"}
    - slot{"location": "Bangalorety"}
    - action_check_location
    - slot{"location_match": "zero"}
    - utter_location_not_found
* restaurant_search{"location": "Bangalore"}
    - slot{"location": "Bangalore"}
    - action_check_location
    - slot{"location_match": "one"}
    - utter_ask_cuisine
* restaurant_search{"cuisine": "chinese"}
    - slot{"cuisine": "chinese"}
    - utter_ask_budget
* restaurant_search{"budget": "399"}
    - slot{"budget": "399"}
    - utter_searching
    - action_restaurant
    - slot{"location": "Bangalore"}
    - utter_ask_for_email_to_send
* affirm
    - utter_ask_email_address
* send_email{"email": "uyhbkjn@gasf.com"}
    - slot{"email": "uyhbkjn@gasf.com"}
    - action_send_email
    - utter_email_sent
    - action_restart

## interactive_story_1
* greet
    - utter_greet
* restaurant_search{"location": "Bangalorety"}
    - slot{"location": "Bangalorety"}
    - action_check_location
    - slot{"location_match": "zero"}
    - utter_location_not_found
* restaurant_search{"location": "Banglaore"}
    - slot{"location": "Banglaore"}
    - action_check_location
    - slot{"location_match": "zero"}
    - utter_location_not_found
* restaurant_search{"location": "Bangalore"}
    - slot{"location": "Bangalore"}
    - action_check_location
    - slot{"location_match": "one"}
    - utter_ask_cuisine
* restaurant_search{"cuisine": "chinese"}
    - slot{"cuisine": "chinese"}
    - utter_ask_budget
* restaurant_search{"budget": "399"}
    - slot{"budget": "399"}
    - utter_searching
    - action_restaurant
    - slot{"location": "Bangalore"}
    - utter_ask_for_email_to_send
* affirm
    - utter_ask_email_address
* send_email{"email": "uyhbkjn@gasf.com"}
    - slot{"email": "uyhbkjn@gasf.com"}
    - action_send_email
    - utter_email_sent
    - action_restart


## interactive_story_1
* greet
    - utter_greet
* restaurant_search{"cuisine": "chinese"}
    - slot{"cuisine": "chinese"}
    - utter_ask_location
* restaurant_search{"location": "Nashiq"}
    - slot{"location": "Nashiq"}
    - action_check_location
    - slot{"location_match": "zero"}
    - utter_location_not_found
* restaurant_search{"location": "Nashik"}
    - slot{"location": "Nashik"}
    - action_check_location
    - slot{"location_match": "one"}
    - utter_ask_budget
* restaurant_search{"budget": "399"}
    - slot{"budget": "399"}
    - utter_searching
    - action_restaurant
    - slot{"location": "Nashik"}
    - utter_ask_for_email_to_send
* send_email{"email": "asdsdad@gasf.com"}
    - slot{"email": "asdsdad@gasf.com"}
    - action_send_email
    - utter_email_sent
    - action_restart

## interactive_story_1
* greet
    - utter_greet
* restaurant_search{"cuisine": "chinese"}
    - slot{"cuisine": "chinese"}
    - utter_ask_location
* restaurant_search{"location": "Nashiq"}
    - slot{"location": "Nashiq"}
    - action_check_location
    - slot{"location_match": "zero"}
    - utter_location_not_found
* restaurant_search{"location": "Nashiqw"}
    - slot{"location": "Nashiqw"}
    - action_check_location
    - slot{"location_match": "zero"}
    - utter_location_not_found
* restaurant_search{"location": "Nashik"}
    - slot{"location": "Nashik"}
    - action_check_location
    - slot{"location_match": "one"}
    - utter_ask_budget
* restaurant_search{"budget": "399"}
    - slot{"budget": "399"}
    - utter_searching
    - action_restaurant
    - slot{"location": "Nashik"}
    - utter_ask_for_email_to_send
* send_email{"email": "asdsdad@gasf.com"}
    - slot{"email": "asdsdad@gasf.com"}
    - action_send_email
    - utter_email_sent
    - action_restart

## interactive_story_1
* greet
    - utter_greet
* restaurant_search{"cuisine": "chinese", "location": "Patnait"}
    - slot{"cuisine": "chinese"}
    - slot{"location": "Patna"}
    - action_check_location
    - slot{"location_match": "zero"}
    - utter_location_not_found
* restaurant_search{"location": "Patna"}
    - slot{"location": "Patna"}
    - action_check_location
    - slot{"location_match": "one"}
    - utter_ask_budget
* restaurant_search{"budget": "399"}
    - slot{"budget": "399"}
    - utter_searching
    - action_restaurant
    - slot{"location": "Patna"}
    - utter_ask_for_email_to_send
* send_email{"email": "shashit95@gmail.com"}
    - slot{"email": "shashit95@gmail.com"}
    - action_send_email
    - utter_email_sent
    - action_restart


## interactive_story_1
* greet
    - utter_greet
* restaurant_search{"cuisine": "chinese", "location": "Patnait"}
    - slot{"cuisine": "chinese"}
    - slot{"location": "Patna"}
    - action_check_location
    - slot{"location_match": "zero"}
    - utter_location_not_found
* restaurant_search{"location": "Patnaii"}
    - slot{"location": "Patnaii"}
    - action_check_location
    - slot{"location_match": "zero"}
    - utter_location_not_found
* restaurant_search{"location": "Patna"}
    - slot{"location": "Patna"}
    - action_check_location
    - slot{"location_match": "one"}
    - utter_ask_budget
* restaurant_search{"budget": "399"}
    - slot{"budget": "399"}
    - utter_searching
    - action_restaurant
    - slot{"location": "Patna"}
    - utter_ask_for_email_to_send
* send_email{"email": "shashit95@gmail.com"}
    - slot{"email": "shashit95@gmail.com"}
    - action_send_email
    - utter_email_sent
    - action_restart

##interactive_story_1
* greet
    - utter_greet
* restaurant_search
    - utter_ask_location
* restaurant_search{"location": "delhsdadi"}
    - slot{"location": "delhsdadi"}
    - action_check_location
    - slot{"location_match": "zero"}
    - utter_location_not_found
* restaurant_search{"location": "delhi"}
    - slot{"location": "delhi"}
    - action_check_location
    - slot{"location_match": "one"}
    - utter_ask_cuisine
* restaurant_search{"cuisine": "chinese"}
    - slot{"cuisine": "chinese"}
    - utter_ask_budget
* restaurant_search{"budget": "399"}
    - slot{"budget": "399"}
    - utter_searching
    - action_restaurant
    - slot{"location": "delhi"}
    - utter_ask_for_email_to_send
* affirm
    - utter_ask_email_address
* send_email{"email": "shashit95@gmail.com"}
    - slot{"email": "shashit95@gmail.com"}
    - action_send_email
    - utter_email_sent
    - action_restart

##interactive_story_1
* greet
    - utter_greet
* restaurant_search
    - utter_ask_location
* restaurant_search{"location": "delhsdadi"}
    - slot{"location": "delhsdadi"}
    - action_check_location
    - slot{"location_match": "zero"}
    - utter_location_not_found
* restaurant_search{"location": "dlehi"}
    - slot{"location": "dlehi"}
    - action_check_location
    - slot{"location_match": "zero"}
    - utter_location_not_found
* restaurant_search{"location": "delhi"}
    - slot{"location": "delhi"}
    - action_check_location
    - slot{"location_match": "one"}
    - utter_ask_cuisine
* restaurant_search{"cuisine": "chinese"}
    - slot{"cuisine": "chinese"}
    - utter_ask_budget
* restaurant_search{"budget": "399"}
    - slot{"budget": "399"}
    - utter_searching
    - action_restaurant
    - slot{"location": "delhi"}
    - utter_ask_for_email_to_send
* affirm
    - utter_ask_email_address
* send_email{"email": "shashit95@gmail.com"}
    - slot{"email": "shashit95@gmail.com"}
    - action_send_email
    - utter_email_sent
    - action_restart

##interactive_story_1
* greet
    - utter_greet
* restaurant_search
    - utter_ask_location
* restaurant_search{"location": "delhsdadi"}
    - slot{"location": "delhsdadi"}
    - action_check_location
    - slot{"location_match": "zero"}
    - utter_location_not_found
* deny
    - utter_goodbye
    - action_restart

##interactive_story_1
* greet
    - utter_greet
* restaurant_search
    - utter_ask_location
* restaurant_search{"location": "delhsdadi"}
    - slot{"location": "delhsdadi"}
    - action_check_location
    - slot{"location_match": "zero"}
    - utter_location_not_found
* goodbye
    - utter_goodbye
    - action_restart


##interactive_story_1
* greet
    - utter_greet
* restaurant_search
    - utter_ask_location
* restaurant_search{"location": "delhsdadi"}
    - slot{"location": "delhsdadi"}
    - action_check_location
    - slot{"location_match": "zero"}
    - utter_location_not_found
* restaurant_search{"location": "dlehi"}
    - slot{"location": "dlehi"}
    - action_check_location
    - slot{"location_match": "zero"}
    - utter_location_not_found
* goodbye
    - utter_goodbye
    - action_restart


##interactive_story_1
* greet
    - utter_greet
* restaurant_search
    - utter_ask_location
* restaurant_search{"location": "delhsdadi"}
    - slot{"location": "delhsdadi"}
    - action_check_location
    - slot{"location_match": "zero"}
    - utter_location_not_found
* restaurant_search{"location": "dlehi"}
    - slot{"location": "dlehi"}
    - action_check_location
    - slot{"location_match": "zero"}
    - utter_location_not_found
* deny
    - utter_goodbye
    - action_restart


## interactive_story_1
* greet
    - utter_greet
* restaurant_search{"location": "Bangalorety"}
    - slot{"location": "Bangalorety"}
    - action_check_location
    - slot{"location_match": "zero"}
    - utter_location_not_found
* restaurant_search{"location": "Bangalore"}
    - slot{"location": "Bangalore"}
    - action_check_location
    - slot{"location_match": "one"}
    - utter_ask_cuisine
* restaurant_search{"cuisine": "chinese"}
    - slot{"cuisine": "chinese"}
    - utter_ask_budget
* restaurant_search{"budget": "399"}
    - slot{"budget": "399"}
    - utter_searching
    - action_restaurant
    - slot{"location": "Bangalore"}
    - utter_ask_for_email_to_send
* affirm
    - utter_ask_email_address
* send_email{"email": "uyhbkjn@gasf.com"}
    - slot{"email": "uyhbkjn@gasf.com"}
    - action_send_email
    - utter_email_sent
    - action_restart

## interactive_story_1
* greet
    - utter_greet
* restaurant_search{"location": "Bangalorety"}
    - slot{"location": "Bangalorety"}
    - action_check_location
    - slot{"location_match": "zero"}
    - utter_location_not_found
* restaurant_search{"location": "Banglaore"}
    - slot{"location": "Banglaore"}
    - action_check_location
    - slot{"location_match": "zero"}
    - utter_location_not_found
* restaurant_search{"location": "Bangalore"}
    - slot{"location": "Bangalore"}
    - action_check_location
    - slot{"location_match": "one"}
    - utter_ask_cuisine
* restaurant_search{"cuisine": "chinese"}
    - slot{"cuisine": "chinese"}
    - utter_ask_budget
* restaurant_search{"budget": "399"}
    - slot{"budget": "399"}
    - utter_searching
    - action_restaurant
    - slot{"location": "Bangalore"}
    - utter_ask_for_email_to_send
* affirm
    - utter_ask_email_address
* send_email{"email": "uyhbkjn@gasf.com"}
    - slot{"email": "uyhbkjn@gasf.com"}
    - action_send_email
    - utter_email_sent
    - action_restart


## interactive_story_1
* greet
    - utter_greet
* restaurant_search{"cuisine": "chinese"}
    - slot{"cuisine": "chinese"}
    - utter_ask_location
* restaurant_search{"location": "Nashiq"}
    - slot{"location": "Nashiq"}
    - action_check_location
    - slot{"location_match": "zero"}
    - utter_location_not_found
* restaurant_search{"location": "Nashik"}
    - slot{"location": "Nashik"}
    - action_check_location
    - slot{"location_match": "one"}
    - utter_ask_budget
* restaurant_search{"budget": "399"}
    - slot{"budget": "399"}
    - utter_searching
    - action_restaurant
    - slot{"location": "Nashik"}
    - utter_ask_for_email_to_send
* send_email{"email": "asdsdad@gasf.com"}
    - slot{"email": "asdsdad@gasf.com"}
    - action_send_email
    - utter_email_sent
    - action_restart

## interactive_story_1
* greet
    - utter_greet
* restaurant_search{"cuisine": "chinese"}
    - slot{"cuisine": "chinese"}
    - utter_ask_location
* restaurant_search{"location": "Nashiq"}
    - slot{"location": "Nashiq"}
    - action_check_location
    - slot{"location_match": "zero"}
    - utter_location_not_found
* restaurant_search{"location": "Nashiqw"}
    - slot{"location": "Nashiqw"}
    - action_check_location
    - slot{"location_match": "zero"}
    - utter_location_not_found
* restaurant_search{"location": "Nashik"}
    - slot{"location": "Nashik"}
    - action_check_location
    - slot{"location_match": "one"}
    - utter_ask_budget
* restaurant_search{"budget": "399"}
    - slot{"budget": "399"}
    - utter_searching
    - action_restaurant
    - slot{"location": "Nashik"}
    - utter_ask_for_email_to_send
* send_email{"email": "asdsdad@gasf.com"}
    - slot{"email": "asdsdad@gasf.com"}
    - action_send_email
    - utter_email_sent
    - action_restart

## interactive_story_1
* greet
    - utter_greet
* restaurant_search{"cuisine": "chinese", "location": "Patnait"}
    - slot{"cuisine": "chinese"}
    - slot{"location": "Patna"}
    - action_check_location
    - slot{"location_match": "zero"}
    - utter_location_not_found
* restaurant_search{"location": "Patna"}
    - slot{"location": "Patna"}
    - action_check_location
    - slot{"location_match": "one"}
    - utter_ask_budget
* restaurant_search{"budget": "399"}
    - slot{"budget": "399"}
    - utter_searching
    - action_restaurant
    - slot{"location": "Patna"}
    - utter_ask_for_email_to_send
* send_email{"email": "shashit95@gmail.com"}
    - slot{"email": "shashit95@gmail.com"}
    - action_send_email
    - utter_email_sent
    - action_restart


## interactive_story_1
* greet
    - utter_greet
* restaurant_search{"cuisine": "chinese", "location": "Patnait"}
    - slot{"cuisine": "chinese"}
    - slot{"location": "Patna"}
    - action_check_location
    - slot{"location_match": "zero"}
    - utter_location_not_found
* restaurant_search{"location": "Patnaii"}
    - slot{"location": "Patnaii"}
    - action_check_location
    - slot{"location_match": "zero"}
    - utter_location_not_found
* restaurant_search{"location": "Patna"}
    - slot{"location": "Patna"}
    - action_check_location
    - slot{"location_match": "one"}
    - utter_ask_budget
* restaurant_search{"budget": "399"}
    - slot{"budget": "399"}
    - utter_searching
    - action_restaurant
    - slot{"location": "Patna"}
    - utter_ask_for_email_to_send
* send_email{"email": "shashit95@gmail.com"}
    - slot{"email": "shashit95@gmail.com"}
    - action_send_email
    - utter_email_sent
    - action_restart

##interactive_story_1
* greet
    - utter_greet
* restaurant_search
    - utter_ask_location
* restaurant_search{"location": "delhsdadi"}
    - slot{"location": "delhsdadi"}
    - action_check_location
    - slot{"location_match": "zero"}
    - utter_location_not_found
* restaurant_search{"location": "delhi"}
    - slot{"location": "delhi"}
    - action_check_location
    - slot{"location_match": "one"}
    - utter_ask_cuisine
* restaurant_search{"cuisine": "chinese"}
    - slot{"cuisine": "chinese"}
    - utter_ask_budget
* restaurant_search{"budget": "399"}
    - slot{"budget": "399"}
    - utter_searching
    - action_restaurant
    - slot{"location": "delhi"}
    - utter_ask_for_email_to_send
* affirm
    - utter_ask_email_address
* send_email{"email": "shashit95@gmail.com"}
    - slot{"email": "shashit95@gmail.com"}
    - action_send_email
    - utter_email_sent
    - action_restart

##interactive_story_1
* greet
    - utter_greet
* restaurant_search
    - utter_ask_location
* restaurant_search{"location": "delhsdadi"}
    - slot{"location": "delhsdadi"}
    - action_check_location
    - slot{"location_match": "zero"}
    - utter_location_not_found
* restaurant_search{"location": "dlehi"}
    - slot{"location": "dlehi"}
    - action_check_location
    - slot{"location_match": "zero"}
    - utter_location_not_found
* restaurant_search{"location": "delhi"}
    - slot{"location": "delhi"}
    - action_check_location
    - slot{"location_match": "one"}
    - utter_ask_cuisine
* restaurant_search{"cuisine": "chinese"}
    - slot{"cuisine": "chinese"}
    - utter_ask_budget
* restaurant_search{"budget": "399"}
    - slot{"budget": "399"}
    - utter_searching
    - action_restaurant
    - slot{"location": "delhi"}
    - utter_ask_for_email_to_send
* affirm
    - utter_ask_email_address
* send_email{"email": "shashit95@gmail.com"}
    - slot{"email": "shashit95@gmail.com"}
    - action_send_email
    - utter_email_sent
    - action_restart

##interactive_story_1
* greet
    - utter_greet
* restaurant_search
    - utter_ask_location
* restaurant_search{"location": "delhsdadi"}
    - slot{"location": "delhsdadi"}
    - action_check_location
    - slot{"location_match": "zero"}
    - utter_location_not_found
* deny
    - utter_goodbye
    - action_restart

##interactive_story_1
* greet
    - utter_greet
* restaurant_search
    - utter_ask_location
* restaurant_search{"location": "delhsdadi"}
    - slot{"location": "delhsdadi"}
    - action_check_location
    - slot{"location_match": "zero"}
    - utter_location_not_found
* goodbye
    - utter_goodbye
    - action_restart


##interactive_story_1
* greet
    - utter_greet
* restaurant_search
    - utter_ask_location
* restaurant_search{"location": "delhsdadi"}
    - slot{"location": "delhsdadi"}
    - action_check_location
    - slot{"location_match": "zero"}
    - utter_location_not_found
* restaurant_search{"location": "dlehi"}
    - slot{"location": "dlehi"}
    - action_check_location
    - slot{"location_match": "zero"}
    - utter_location_not_found
* goodbye
    - utter_goodbye
    - action_restart


##interactive_story_1
* greet
    - utter_greet
* restaurant_search
    - utter_ask_location
* restaurant_search{"location": "delhsdadi"}
    - slot{"location": "delhsdadi"}
    - action_check_location
    - slot{"location_match": "zero"}
    - utter_location_not_found
* restaurant_search{"location": "dlehi"}
    - slot{"location": "dlehi"}
    - action_check_location
    - slot{"location_match": "zero"}
    - utter_location_not_found
* deny
    - utter_goodbye
    - action_restart


## interactive_story_1
* greet
    - utter_greet
* restaurant_search{"location": "Bangalorety"}
    - slot{"location": "Bangalorety"}
    - action_check_location
    - slot{"location_match": "zero"}
    - utter_location_not_found
* restaurant_search{"location": "Bangalore"}
    - slot{"location": "Bangalore"}
    - action_check_location
    - slot{"location_match": "one"}
    - utter_ask_cuisine
* restaurant_search{"cuisine": "chinese"}
    - slot{"cuisine": "chinese"}
    - utter_ask_budget
* restaurant_search{"budget": "399"}
    - slot{"budget": "399"}
    - utter_searching
    - action_restaurant
    - slot{"location": "Bangalore"}
    - utter_ask_for_email_to_send
* affirm
    - utter_ask_email_address
* send_email{"email": "uyhbkjn@gasf.com"}
    - slot{"email": "uyhbkjn@gasf.com"}
    - action_send_email
    - utter_email_sent
    - action_restart

## interactive_story_1
* greet
    - utter_greet
* restaurant_search{"location": "Bangalorety"}
    - slot{"location": "Bangalorety"}
    - action_check_location
    - slot{"location_match": "zero"}
    - utter_location_not_found
* restaurant_search{"location": "Banglaore"}
    - slot{"location": "Banglaore"}
    - action_check_location
    - slot{"location_match": "zero"}
    - utter_location_not_found
* restaurant_search{"location": "Bangalore"}
    - slot{"location": "Bangalore"}
    - action_check_location
    - slot{"location_match": "one"}
    - utter_ask_cuisine
* restaurant_search{"cuisine": "chinese"}
    - slot{"cuisine": "chinese"}
    - utter_ask_budget
* restaurant_search{"budget": "399"}
    - slot{"budget": "399"}
    - utter_searching
    - action_restaurant
    - slot{"location": "Bangalore"}
    - utter_ask_for_email_to_send
* affirm
    - utter_ask_email_address
* send_email{"email": "uyhbkjn@gasf.com"}
    - slot{"email": "uyhbkjn@gasf.com"}
    - action_send_email
    - utter_email_sent
    - action_restart


## interactive_story_1
* greet
    - utter_greet
* restaurant_search{"cuisine": "chinese"}
    - slot{"cuisine": "chinese"}
    - utter_ask_location
* restaurant_search{"location": "Nashiq"}
    - slot{"location": "Nashiq"}
    - action_check_location
    - slot{"location_match": "zero"}
    - utter_location_not_found
* restaurant_search{"location": "Nashik"}
    - slot{"location": "Nashik"}
    - action_check_location
    - slot{"location_match": "one"}
    - utter_ask_budget
* restaurant_search{"budget": "399"}
    - slot{"budget": "399"}
    - utter_searching
    - action_restaurant
    - slot{"location": "Nashik"}
    - utter_ask_for_email_to_send
* send_email{"email": "asdsdad@gasf.com"}
    - slot{"email": "asdsdad@gasf.com"}
    - action_send_email
    - utter_email_sent
    - action_restart

## interactive_story_1
* greet
    - utter_greet
* restaurant_search{"cuisine": "chinese"}
    - slot{"cuisine": "chinese"}
    - utter_ask_location
* restaurant_search{"location": "Nashiq"}
    - slot{"location": "Nashiq"}
    - action_check_location
    - slot{"location_match": "zero"}
    - utter_location_not_found
* restaurant_search{"location": "Nashiqw"}
    - slot{"location": "Nashiqw"}
    - action_check_location
    - slot{"location_match": "zero"}
    - utter_location_not_found
* restaurant_search{"location": "Nashik"}
    - slot{"location": "Nashik"}
    - action_check_location
    - slot{"location_match": "one"}
    - utter_ask_budget
* restaurant_search{"budget": "399"}
    - slot{"budget": "399"}
    - utter_searching
    - action_restaurant
    - slot{"location": "Nashik"}
    - utter_ask_for_email_to_send
* send_email{"email": "asdsdad@gasf.com"}
    - slot{"email": "asdsdad@gasf.com"}
    - action_send_email
    - utter_email_sent
    - action_restart

## interactive_story_1
* greet
    - utter_greet
* restaurant_search{"cuisine": "chinese", "location": "Patnait"}
    - slot{"cuisine": "chinese"}
    - slot{"location": "Patna"}
    - action_check_location
    - slot{"location_match": "zero"}
    - utter_location_not_found
* restaurant_search{"location": "Patna"}
    - slot{"location": "Patna"}
    - action_check_location
    - slot{"location_match": "one"}
    - utter_ask_budget
* restaurant_search{"budget": "399"}
    - slot{"budget": "399"}
    - utter_searching
    - action_restaurant
    - slot{"location": "Patna"}
    - utter_ask_for_email_to_send
* send_email{"email": "shashit95@gmail.com"}
    - slot{"email": "shashit95@gmail.com"}
    - action_send_email
    - utter_email_sent
    - action_restart


## interactive_story_1
* greet
    - utter_greet
* restaurant_search{"cuisine": "chinese", "location": "Patnait"}
    - slot{"cuisine": "chinese"}
    - slot{"location": "Patna"}
    - action_check_location
    - slot{"location_match": "zero"}
    - utter_location_not_found
* restaurant_search{"location": "Patnaii"}
    - slot{"location": "Patnaii"}
    - action_check_location
    - slot{"location_match": "zero"}
    - utter_location_not_found
* restaurant_search{"location": "Patna"}
    - slot{"location": "Patna"}
    - action_check_location
    - slot{"location_match": "one"}
    - utter_ask_budget
* restaurant_search{"budget": "399"}
    - slot{"budget": "399"}
    - utter_searching
    - action_restaurant
    - slot{"location": "Patna"}
    - utter_ask_for_email_to_send
* send_email{"email": "shashit95@gmail.com"}
    - slot{"email": "shashit95@gmail.com"}
    - action_send_email
    - utter_email_sent
    - action_restart

<!-- condition checkpoints -->

<!-- all the restaurant_searchation in one go -->

## interactive_story_1
* greet
    - utter_greet
* restaurant_search{"cuisine": "chinese", "location": "delhi", "budget": "399"}
    - slot{"cuisine": "chinese"}
    - slot{"location": "delhi"}
    - slot{"budget": "399"}
    - action_check_location
    - slot{"location_match": "one"}
    - utter_searching
    - action_restaurant
    - slot{"location": "Patna"}
    - utter_ask_for_email_to_send
* send_email{"email": "shashit95@gmail.com"}
    - slot{"email": "shashit95@gmail.com"}
    - action_send_email
    - utter_email_sent
    - action_restart

## interactive_story_1
* greet
    - utter_greet
* restaurant_search{"cuisine": "chinese", "location": "delhi", "budget": "399"}
    - slot{"cuisine": "chinese"}
    - slot{"location": "delhi"}
    - slot{"budget": "399"}
    - action_check_location
    - slot{"location_match": "one"}
    - utter_searching
    - action_restaurant
    - slot{"location": "Patna"}
    - utter_ask_for_email_to_send
* send_email{"email": "shashit95@gmail.com"}
    - slot{"email": "shashit95@gmail.com"}
    - action_send_email
    - utter_email_sent
    - action_restart

## interactive_story_1
* greet
    - utter_greet
* restaurant_search{"cuisine": "chinese", "location": "delhi", "budget": "399"}
    - slot{"cuisine": "chinese"}
    - slot{"location": "delhi"}
    - slot{"budget": "399"}
    - action_check_location
    - slot{"location_match": "one"}
    - utter_searching
    - action_restaurant
    - slot{"location": "Patna"}
    - utter_ask_for_email_to_send
* send_email{"email": "shashit95@gmail.com"}
    - slot{"email": "shashit95@gmail.com"}
    - action_send_email
    - utter_email_sent
    - action_restart

## interactive_story_1
* greet
    - utter_greet
* restaurant_search{"cuisine": "chinese", "location": "delhi", "budget": "399"}
    - slot{"cuisine": "chinese"}
    - slot{"location": "delhi"}
    - slot{"budget": "399"}
    - action_check_location
    - slot{"location_match": "one"}
    - utter_searching
    - action_restaurant
    - slot{"location": "Patna"}
    - utter_ask_for_email_to_send
* send_email{"email": "shashit95@gmail.com"}
    - slot{"email": "shashit95@gmail.com"}
    - action_send_email
    - utter_email_sent
    - action_restart

## interactive_story_1
* greet
    - utter_greet
* restaurant_search{"cuisine": "chinese", "location": "delhi", "budget": "399"}
    - slot{"cuisine": "chinese"}
    - slot{"location": "delhi"}
    - slot{"budget": "399"}
    - action_check_location
    - slot{"location_match": "one"}
    - utter_searching
    - action_restaurant
    - slot{"location": "Patna"}
    - utter_ask_for_email_to_send
* send_email{"email": "shashit95@gmail.com"}
    - slot{"email": "shashit95@gmail.com"}
    - action_send_email
    - utter_email_sent
    - action_restart

## interactive_story_1
* greet
    - utter_greet
* restaurant_search{"cuisine": "chinese", "location": "delhi", "budget": "399"}
    - slot{"cuisine": "chinese"}
    - slot{"location": "delhi"}
    - slot{"budget": "399"}
    - action_check_location
    - slot{"location_match": "one"}
    - utter_searching
    - action_restaurant
    - slot{"location": "Patna"}
    - utter_ask_for_email_to_send
* send_email{"email": "shashit95@gmail.com"}
    - slot{"email": "shashit95@gmail.com"}
    - action_send_email
    - utter_email_sent
    - action_restart

## interactive_story_1
* greet
    - utter_greet
* restaurant_search{"cuisine": "chinese", "location": "delhi", "budget": "399"}
    - slot{"cuisine": "chinese"}
    - slot{"location": "delhi"}
    - slot{"budget": "399"}
    - action_check_location
    - slot{"location_match": "one"}
    - utter_searching
    - action_restaurant
    - slot{"location": "Patna"}
    - utter_ask_for_email_to_send
* send_email{"email": "shashit95@gmail.com"}
    - slot{"email": "shashit95@gmail.com"}
    - action_send_email
    - utter_email_sent
    - action_restart


## interactive_story_1
* greet
    - utter_greet
* restaurant_search{"cuisine": "chinese", "location": "delhi", "budget": "399"}
    - slot{"cuisine": "chinese"}
    - slot{"location": "delhi"}
    - slot{"budget": "399"}
    - action_check_location
    - slot{"location_match": "one"}
    - utter_searching
    - action_restaurant
    - slot{"location": "Patna"}
    - utter_ask_for_email_to_send
* send_email{"email": "shashit95@gmail.com"}
    - slot{"email": "shashit95@gmail.com"}
    - action_send_email
    - utter_email_sent
    - action_restart

## interactive_story_1
* greet
    - utter_greet
* restaurant_search{"cuisine": "chinese", "location": "delhi", "budget": "399"}
    - slot{"cuisine": "chinese"}
    - slot{"location": "delhi"}
    - slot{"budget": "399"}
    - action_check_location
    - slot{"location_match": "one"}
    - utter_searching
    - action_restaurant
    - slot{"location": "Patna"}
    - utter_ask_for_email_to_send
* send_email{"email": "shashit95@gmail.com"}
    - slot{"email": "shashit95@gmail.com"}
    - action_send_email
    - utter_email_sent
    - action_restart

## interactive_story_1
* greet
    - utter_greet
* restaurant_search{"cuisine": "chinese", "location": "delhi", "budget": "399"}
    - slot{"cuisine": "chinese"}
    - slot{"location": "delhi"}
    - slot{"budget": "399"}
    - action_check_location
    - slot{"location_match": "one"}
    - utter_searching
    - action_restaurant
    - slot{"location": "Patna"}
    - utter_ask_for_email_to_send
* send_email{"email": "shashit95@gmail.com"}
    - slot{"email": "shashit95@gmail.com"}
    - action_send_email
    - utter_email_sent
    - action_restart

## interactive_story_1
* greet
    - utter_greet
* restaurant_search{"cuisine": "chinese", "location": "delhi", "budget": "399"}
    - slot{"cuisine": "chinese"}
    - slot{"location": "delhi"}
    - slot{"budget": "399"}
    - action_check_location
    - slot{"location_match": "one"}
    - utter_searching
    - action_restaurant
    - slot{"location": "Patna"}
    - utter_ask_for_email_to_send
* send_email{"email": "shashit95@gmail.com"}
    - slot{"email": "shashit95@gmail.com"}
    - action_send_email
    - utter_email_sent
    - action_restart

## interactive_story_1
* greet
    - utter_greet
* restaurant_search{"cuisine": "chinese", "location": "delhi", "budget": "399"}
    - slot{"cuisine": "chinese"}
    - slot{"location": "delhi"}
    - slot{"budget": "399"}
    - action_check_location
    - slot{"location_match": "one"}
    - utter_searching
    - action_restaurant
    - slot{"location": "Patna"}
    - utter_ask_for_email_to_send
* send_email{"email": "shashit95@gmail.com"}
    - slot{"email": "shashit95@gmail.com"}
    - action_send_email
    - utter_email_sent
    - action_restart

## interactive_story_1
* greet
    - utter_greet
* restaurant_search{"cuisine": "chinese", "location": "delhi", "budget": "399"}
    - slot{"cuisine": "chinese"}
    - slot{"location": "delhi"}
    - slot{"budget": "399"}
    - action_check_location
    - slot{"location_match": "one"}
    - utter_searching
    - action_restaurant
    - slot{"location": "Patna"}
    - utter_ask_for_email_to_send
* send_email{"email": "shashit95@gmail.com"}
    - slot{"email": "shashit95@gmail.com"}
    - action_send_email
    - utter_email_sent
    - action_restart

## interactive_story_1
* greet
    - utter_greet
* restaurant_search{"cuisine": "chinese", "location": "delhi", "budget": "399"}
    - slot{"cuisine": "chinese"}
    - slot{"location": "delhi"}
    - slot{"budget": "399"}
    - action_check_location
    - slot{"location_match": "one"}
    - utter_searching
    - action_restaurant
    - slot{"location": "Patna"}
    - utter_ask_for_email_to_send
* send_email{"email": "shashit95@gmail.com"}
    - slot{"email": "shashit95@gmail.com"}
    - action_send_email
    - utter_email_sent
    - action_restart

## interactive_story_1
* greet
    - utter_greet
* restaurant_search{"cuisine": "chinese", "location": "delhi", "budget": "399"}
    - slot{"cuisine": "chinese"}
    - slot{"location": "delhi"}
    - slot{"budget": "399"}
    - action_check_location
    - slot{"location_match": "one"}
    - utter_searching
    - action_restaurant
    - slot{"location": "Patna"}
    - utter_ask_for_email_to_send
* send_email{"email": "shashit95@gmail.com"}
    - slot{"email": "shashit95@gmail.com"}
    - action_send_email
    - utter_email_sent
    - action_restart

## interactive_story_1
* greet
    - utter_greet
* restaurant_search{"cuisine": "chinese", "location": "delhi", "budget": "399"}
    - slot{"cuisine": "chinese"}
    - slot{"location": "delhi"}
    - slot{"budget": "399"}
    - action_check_location
    - slot{"location_match": "one"}
    - utter_searching
    - action_restaurant
    - slot{"location": "Patna"}
    - utter_ask_for_email_to_send
* send_email{"email": "shashit95@gmail.com"}
    - slot{"email": "shashit95@gmail.com"}
    - action_send_email
    - utter_email_sent
    - action_restart

## interactive_story_1
* greet
    - utter_greet
* restaurant_search{"cuisine": "chinese", "location": "delhi", "budget": "399"}
    - slot{"cuisine": "chinese"}
    - slot{"location": "delhi"}
    - slot{"budget": "399"}
    - action_check_location
    - slot{"location_match": "one"}
    - utter_searching
    - action_restaurant
    - slot{"location": "Patna"}
    - utter_ask_for_email_to_send
* send_email{"email": "shashit95@gmail.com"}
    - slot{"email": "shashit95@gmail.com"}
    - action_send_email
    - utter_email_sent
    - action_restart

## interactive_story_1
* greet
    - utter_greet
* restaurant_search{"cuisine": "chinese", "location": "delhi", "budget": "399"}
    - slot{"cuisine": "chinese"}
    - slot{"location": "delhi"}
    - slot{"budget": "399"}
    - action_check_location
    - slot{"location_match": "one"}
    - utter_searching
    - action_restaurant
    - slot{"location": "Patna"}
    - utter_ask_for_email_to_send
* send_email{"email": "shashit95@gmail.com"}
    - slot{"email": "shashit95@gmail.com"}
    - action_send_email
    - utter_email_sent
    - action_restart

## interactive_story_1
* greet
    - utter_greet
* restaurant_search{"cuisine": "chinese", "location": "delhi", "budget": "399"}
    - slot{"cuisine": "chinese"}
    - slot{"location": "delhi"}
    - slot{"budget": "399"}
    - action_check_location
    - slot{"location_match": "one"}
    - utter_searching
    - action_restaurant
    - slot{"location": "Patna"}
    - utter_ask_for_email_to_send
* send_email{"email": "shashit95@gmail.com"}
    - slot{"email": "shashit95@gmail.com"}
    - action_send_email
    - utter_email_sent
    - action_restart

## interactive_story_1
* greet
    - utter_greet
* restaurant_search{"cuisine": "chinese", "location": "delhi", "budget": "399"}
    - slot{"cuisine": "chinese"}
    - slot{"location": "delhi"}
    - slot{"budget": "399"}
    - action_check_location
    - slot{"location_match": "one"}
    - utter_searching
    - action_restaurant
    - slot{"location": "Patna"}
    - utter_ask_for_email_to_send
* send_email{"email": "shashit95@gmail.com"}
    - slot{"email": "shashit95@gmail.com"}
    - action_send_email
    - utter_email_sent
    - action_restart

## interactive_story_1
* greet
    - utter_greet
* restaurant_search{"cuisine": "chinese", "location": "delhi", "budget": "399"}
    - slot{"cuisine": "chinese"}
    - slot{"location": "delhi"}
    - slot{"budget": "399"}
    - action_check_location
    - slot{"location_match": "one"}
    - utter_searching
    - action_restaurant
    - slot{"location": "Patna"}
    - utter_ask_for_email_to_send
* send_email{"email": "shashit95@gmail.com"}
    - slot{"email": "shashit95@gmail.com"}
    - action_send_email
    - utter_email_sent
    - action_restart

## interactive_story_1
* greet
    - utter_greet
* restaurant_search{"cuisine": "chinese", "location": "delhi", "budget": "399"}
    - slot{"cuisine": "chinese"}
    - slot{"location": "delhi"}
    - slot{"budget": "399"}
    - action_check_location
    - slot{"location_match": "one"}
    - utter_searching
    - action_restaurant
    - slot{"location": "Patna"}
    - utter_ask_for_email_to_send
* send_email{"email": "shashit95@gmail.com"}
    - slot{"email": "shashit95@gmail.com"}
    - action_send_email
    - utter_email_sent
    - action_restart

## interactive_story_1
* greet
    - utter_greet
* restaurant_search{"cuisine": "chinese", "location": "delhi", "budget": "399"}
    - slot{"cuisine": "chinese"}
    - slot{"location": "delhi"}
    - slot{"budget": "399"}
    - action_check_location
    - slot{"location_match": "one"}
    - utter_searching
    - action_restaurant
    - slot{"location": "Patna"}
    - utter_ask_for_email_to_send
* send_email{"email": "shashit95@gmail.com"}
    - slot{"email": "shashit95@gmail.com"}
    - action_send_email
    - utter_email_sent
    - action_restart

## interactive_story_1
* greet
    - utter_greet
* restaurant_search{"location": "delhi", "budget": "2000"}
    - slot{"location": "delhi"}
    - slot{"budget": "2000"}
    - action_check_location
    - slot{"location_match": "one"}
    - utter_ask_cuisine
* restaurant_search{"cuisine": "chinese"}
    - slot{"cuisine": "chinese"}
    - utter_searching
    - action_restaurant
    - slot{"location": "delhi"}
    - utter_ask_for_email_to_send
* send_email{"email": "shashit95@gmail.com"}
    - slot{"email": "shashit95@gmail.com"}
    - action_send_email
    - utter_email_sent
    - action_restart

## interactive_story_1
* greet
    - utter_greet
* restaurant_search{"location": "delhi", "budget": "2000"}
    - slot{"location": "delhi"}
    - slot{"budget": "2000"}
    - action_check_location
    - slot{"location_match": "one"}
    - utter_ask_cuisine
* restaurant_search{"cuisine": "chinese"}
    - slot{"cuisine": "chinese"}
    - utter_searching
    - action_restaurant
    - slot{"location": "delhi"}
    - utter_ask_for_email_to_send
* send_email{"email": "shashit95@gmail.com"}
    - slot{"email": "shashit95@gmail.com"}
    - action_send_email
    - utter_email_sent
    - action_restart

## interactive_story_1
* greet
    - utter_greet
* restaurant_search{"location": "delhi", "budget": "2000"}
    - slot{"location": "delhi"}
    - slot{"budget": "2000"}
    - action_check_location
    - slot{"location_match": "one"}
    - utter_ask_cuisine
* restaurant_search{"cuisine": "chinese"}
    - slot{"cuisine": "chinese"}
    - utter_searching
    - action_restaurant
    - slot{"location": "delhi"}
    - utter_ask_for_email_to_send
* send_email{"email": "shashit95@gmail.com"}
    - slot{"email": "shashit95@gmail.com"}
    - action_send_email
    - utter_email_sent
    - action_restart

## interactive_story_1
* greet
    - utter_greet
* restaurant_search{"location": "delhi", "budget": "2000"}
    - slot{"location": "delhi"}
    - slot{"budget": "2000"}
    - action_check_location
    - slot{"location_match": "one"}
    - utter_ask_cuisine
* restaurant_search{"cuisine": "chinese"}
    - slot{"cuisine": "chinese"}
    - utter_searching
    - action_restaurant
    - slot{"location": "delhi"}
    - utter_ask_for_email_to_send
* send_email{"email": "shashit95@gmail.com"}
    - slot{"email": "shashit95@gmail.com"}
    - action_send_email
    - utter_email_sent
    - action_restart

## interactive_story_1
* greet
    - utter_greet
* restaurant_search{"location": "delhi", "budget": "2000"}
    - slot{"location": "delhi"}
    - slot{"budget": "2000"}
    - action_check_location
    - slot{"location_match": "one"}
    - utter_ask_cuisine
* restaurant_search{"cuisine": "chinese"}
    - slot{"cuisine": "chinese"}
    - utter_searching
    - action_restaurant
    - slot{"location": "delhi"}
    - utter_ask_for_email_to_send
* send_email{"email": "shashit95@gmail.com"}
    - slot{"email": "shashit95@gmail.com"}
    - action_send_email
    - utter_email_sent
    - action_restart

## interactive_story_1
* greet
    - utter_greet
* restaurant_search{"location": "delhi", "budget": "2000"}
    - slot{"location": "delhi"}
    - slot{"budget": "2000"}
    - action_check_location
    - slot{"location_match": "one"}
    - utter_ask_cuisine
* restaurant_search{"cuisine": "chinese"}
    - slot{"cuisine": "chinese"}
    - utter_searching
    - action_restaurant
    - slot{"location": "delhi"}
    - utter_ask_for_email_to_send
* send_email{"email": "shashit95@gmail.com"}
    - slot{"email": "shashit95@gmail.com"}
    - action_send_email
    - utter_email_sent
    - action_restart

## interactive_story_1
* greet
    - utter_greet
* restaurant_search{"location": "delhi", "budget": "2000"}
    - slot{"location": "delhi"}
    - slot{"budget": "2000"}
    - action_check_location
    - slot{"location_match": "one"}
    - utter_ask_cuisine
* restaurant_search{"cuisine": "chinese"}
    - slot{"cuisine": "chinese"}
    - utter_searching
    - action_restaurant
    - slot{"location": "delhi"}
    - utter_ask_for_email_to_send
* send_email{"email": "shashit95@gmail.com"}
    - slot{"email": "shashit95@gmail.com"}
    - action_send_email
    - utter_email_sent
    - action_restart

## interactive_story_1
* greet
    - utter_greet
* restaurant_search{"location": "delhi", "budget": "2000"}
    - slot{"location": "delhi"}
    - slot{"budget": "2000"}
    - action_check_location
    - slot{"location_match": "one"}
    - utter_ask_cuisine
* restaurant_search{"cuisine": "chinese"}
    - slot{"cuisine": "chinese"}
    - utter_searching
    - action_restaurant
    - slot{"location": "delhi"}
    - utter_ask_for_email_to_send
* send_email{"email": "shashit95@gmail.com"}
    - slot{"email": "shashit95@gmail.com"}
    - action_send_email
    - utter_email_sent
    - action_restart

## interactive_story_1
* greet
    - utter_greet
* restaurant_search{"location": "delhi", "budget": "2000"}
    - slot{"location": "delhi"}
    - slot{"budget": "2000"}
    - action_check_location
    - slot{"location_match": "one"}
    - utter_ask_cuisine
* restaurant_search{"cuisine": "chinese"}
    - slot{"cuisine": "chinese"}
    - utter_searching
    - action_restaurant
    - slot{"location": "delhi"}
    - utter_ask_for_email_to_send
* send_email{"email": "shashit95@gmail.com"}
    - slot{"email": "shashit95@gmail.com"}
    - action_send_email
    - utter_email_sent
    - action_restart

## interactive_story_1
* greet
    - utter_greet
* restaurant_search{"location": "delhi", "budget": "2000"}
    - slot{"location": "delhi"}
    - slot{"budget": "2000"}
    - action_check_location
    - slot{"location_match": "one"}
    - utter_ask_cuisine
* restaurant_search{"cuisine": "chinese"}
    - slot{"cuisine": "chinese"}
    - utter_searching
    - action_restaurant
    - slot{"location": "delhi"}
    - utter_ask_for_email_to_send
* send_email{"email": "shashit95@gmail.com"}
    - slot{"email": "shashit95@gmail.com"}
    - action_send_email
    - utter_email_sent
    - action_restart

## interactive_story_1
* greet
    - utter_greet
* restaurant_search{"location": "delhi", "budget": "2000"}
    - slot{"location": "delhi"}
    - slot{"budget": "2000"}
    - action_check_location
    - slot{"location_match": "one"}
    - utter_ask_cuisine
* restaurant_search{"cuisine": "chinese"}
    - slot{"cuisine": "chinese"}
    - utter_searching
    - action_restaurant
    - slot{"location": "delhi"}
    - utter_ask_for_email_to_send
* send_email{"email": "shashit95@gmail.com"}
    - slot{"email": "shashit95@gmail.com"}
    - action_send_email
    - utter_email_sent
    - action_restart

## interactive_story_1
* greet
    - utter_greet
* restaurant_search{"location": "delhi", "budget": "2000"}
    - slot{"location": "delhi"}
    - slot{"budget": "2000"}
    - action_check_location
    - slot{"location_match": "one"}
    - utter_ask_cuisine
* restaurant_search{"cuisine": "chinese"}
    - slot{"cuisine": "chinese"}
    - utter_searching
    - action_restaurant
    - slot{"location": "delhi"}
    - utter_ask_for_email_to_send
* send_email{"email": "shashit95@gmail.com"}
    - slot{"email": "shashit95@gmail.com"}
    - action_send_email
    - utter_email_sent
    - action_restart

## interactive_story_1
* greet
    - utter_greet
* restaurant_search{"location": "delhi", "budget": "2000"}
    - slot{"location": "delhi"}
    - slot{"budget": "2000"}
    - action_check_location
    - slot{"location_match": "one"}
    - utter_ask_cuisine
* restaurant_search{"cuisine": "chinese"}
    - slot{"cuisine": "chinese"}
    - utter_searching
    - action_restaurant
    - slot{"location": "delhi"}
    - utter_ask_for_email_to_send
* send_email{"email": "shashit95@gmail.com"}
    - slot{"email": "shashit95@gmail.com"}
    - action_send_email
    - utter_email_sent
    - action_restart

## interactive_story_1
* greet
    - utter_greet
* restaurant_search{"location": "delhi", "budget": "2000"}
    - slot{"location": "delhi"}
    - slot{"budget": "2000"}
    - action_check_location
    - slot{"location_match": "one"}
    - utter_ask_cuisine
* restaurant_search{"cuisine": "chinese"}
    - slot{"cuisine": "chinese"}
    - utter_searching
    - action_restaurant
    - slot{"location": "delhi"}
    - utter_ask_for_email_to_send
* send_email{"email": "shashit95@gmail.com"}
    - slot{"email": "shashit95@gmail.com"}
    - action_send_email
    - utter_email_sent
    - action_restart

## interactive_story_1
* greet
    - utter_greet
* restaurant_search{"location": "delhi", "budget": "2000"}
    - slot{"location": "delhi"}
    - slot{"budget": "2000"}
    - action_check_location
    - slot{"location_match": "one"}
    - utter_ask_cuisine
* restaurant_search{"cuisine": "chinese"}
    - slot{"cuisine": "chinese"}
    - utter_searching
    - action_restaurant
    - slot{"location": "delhi"}
    - utter_ask_for_email_to_send
* send_email{"email": "shashit95@gmail.com"}
    - slot{"email": "shashit95@gmail.com"}
    - action_send_email
    - utter_email_sent
    - action_restart

## interactive_story_1
* greet
    - utter_greet
* restaurant_search{"location": "delhi", "budget": "2000"}
    - slot{"location": "delhi"}
    - slot{"budget": "2000"}
    - action_check_location
    - slot{"location_match": "one"}
    - utter_ask_cuisine
* restaurant_search{"cuisine": "chinese"}
    - slot{"cuisine": "chinese"}
    - utter_searching
    - action_restaurant
    - slot{"location": "delhi"}
    - utter_ask_for_email_to_send
* send_email{"email": "shashit95@gmail.com"}
    - slot{"email": "shashit95@gmail.com"}
    - action_send_email
    - utter_email_sent
    - action_restart

## interactive_story_1
* greet
    - utter_greet
* restaurant_search{"location": "delhi", "budget": "2000"}
    - slot{"location": "delhi"}
    - slot{"budget": "2000"}
    - action_check_location
    - slot{"location_match": "one"}
    - utter_ask_cuisine
* restaurant_search{"cuisine": "chinese"}
    - slot{"cuisine": "chinese"}
    - utter_searching
    - action_restaurant
    - slot{"location": "delhi"}
    - utter_ask_for_email_to_send
* send_email{"email": "shashit95@gmail.com"}
    - slot{"email": "shashit95@gmail.com"}
    - action_send_email
    - utter_email_sent
    - action_restart

## interactive_story_1
* greet
    - utter_greet
* restaurant_search{"location": "delhi", "budget": "2000"}
    - slot{"location": "delhi"}
    - slot{"budget": "2000"}
    - action_check_location
    - slot{"location_match": "one"}
    - utter_ask_cuisine
* restaurant_search{"cuisine": "chinese"}
    - slot{"cuisine": "chinese"}
    - utter_searching
    - action_restaurant
    - slot{"location": "delhi"}
    - utter_ask_for_email_to_send
* send_email{"email": "shashit95@gmail.com"}
    - slot{"email": "shashit95@gmail.com"}
    - action_send_email
    - utter_email_sent
    - action_restart

## interactive_story_1
* greet
    - utter_greet
* restaurant_search{"location": "delhi", "budget": "2000"}
    - slot{"location": "delhi"}
    - slot{"budget": "2000"}
    - action_check_location
    - slot{"location_match": "one"}
    - utter_ask_cuisine
* restaurant_search{"cuisine": "chinese"}
    - slot{"cuisine": "chinese"}
    - utter_searching
    - action_restaurant
    - slot{"location": "delhi"}
    - utter_ask_for_email_to_send
* send_email{"email": "shashit95@gmail.com"}
    - slot{"email": "shashit95@gmail.com"}
    - action_send_email
    - utter_email_sent
    - action_restart

## interactive_story_1
* greet
    - utter_greet
* restaurant_search{"location": "delhi", "budget": "2000"}
    - slot{"location": "delhi"}
    - slot{"budget": "2000"}
    - action_check_location
    - slot{"location_match": "one"}
    - utter_ask_cuisine
* restaurant_search{"cuisine": "chinese"}
    - slot{"cuisine": "chinese"}
    - utter_searching
    - action_restaurant
    - slot{"location": "delhi"}
    - utter_ask_for_email_to_send
* send_email{"email": "shashit95@gmail.com"}
    - slot{"email": "shashit95@gmail.com"}
    - action_send_email
    - utter_email_sent
    - action_restart

## interactive_story_1
* greet
    - utter_greet
* restaurant_search{"location": "delhi", "budget": "2000"}
    - slot{"location": "delhi"}
    - slot{"budget": "2000"}
    - action_check_location
    - slot{"location_match": "one"}
    - utter_ask_cuisine
* restaurant_search{"cuisine": "chinese"}
    - slot{"cuisine": "chinese"}
    - utter_searching
    - action_restaurant
    - slot{"location": "delhi"}
    - utter_ask_for_email_to_send
* send_email{"email": "shashit95@gmail.com"}
    - slot{"email": "shashit95@gmail.com"}
    - action_send_email
    - utter_email_sent
    - action_restart

## interactive_story_1
* greet
    - utter_greet
* restaurant_search{"location": "delhi", "budget": "2000"}
    - slot{"location": "delhi"}
    - slot{"budget": "2000"}
    - action_check_location
    - slot{"location_match": "one"}
    - utter_ask_cuisine
* restaurant_search{"cuisine": "chinese"}
    - slot{"cuisine": "chinese"}
    - utter_searching
    - action_restaurant
    - slot{"location": "delhi"}
    - utter_ask_for_email_to_send
* send_email{"email": "shashit95@gmail.com"}
    - slot{"email": "shashit95@gmail.com"}
    - action_send_email
    - utter_email_sent
    - action_restart

<!-- starting with cuisine and budget -->

## interactive_story_1
* greet
    - utter_greet
* restaurant_search{"cuisine": "chinese", "budget": "2000"}
    - slot{"cuisine": "chinese"}
    - slot{"budget": "2000"}
    - utter_ask_location
* restaurant_search{"location": "delhi"}
    - slot{"location": "delhi"}
    - action_check_location
    - slot{"location_match": "one"}
    - utter_searching
    - action_restaurant
    - slot{"location": "delhi"}
    - utter_ask_for_email_to_send
* send_email{"email": "shashit95@gmail.com"}
    - slot{"email": "shashit95@gmail.com"}
    - action_send_email
    - utter_email_sent
    - action_restart

## interactive_story_1
* greet
    - utter_greet
* restaurant_search{"cuisine": "chinese", "budget": "2000"}
    - slot{"cuisine": "chinese"}
    - slot{"budget": "2000"}
    - utter_ask_location
* restaurant_search{"location": "delhi"}
    - slot{"location": "delhi"}
    - action_check_location
    - slot{"location_match": "one"}
    - utter_searching
    - action_restaurant
    - slot{"location": "delhi"}
    - utter_ask_for_email_to_send
* send_email{"email": "shashit95@gmail.com"}
    - slot{"email": "shashit95@gmail.com"}
    - action_send_email
    - utter_email_sent
    - action_restart

## interactive_story_1
* greet
    - utter_greet
* restaurant_search{"cuisine": "chinese", "budget": "2000"}
    - slot{"cuisine": "chinese"}
    - slot{"budget": "2000"}
    - utter_ask_location
* restaurant_search{"location": "delhi"}
    - slot{"location": "delhi"}
    - action_check_location
    - slot{"location_match": "one"}
    - utter_searching
    - action_restaurant
    - slot{"location": "delhi"}
    - utter_ask_for_email_to_send
* send_email{"email": "shashit95@gmail.com"}
    - slot{"email": "shashit95@gmail.com"}
    - action_send_email
    - utter_email_sent
    - action_restart

## interactive_story_1
* greet
    - utter_greet
* restaurant_search{"cuisine": "chinese", "budget": "2000"}
    - slot{"cuisine": "chinese"}
    - slot{"budget": "2000"}
    - utter_ask_location
* restaurant_search{"location": "delhi"}
    - slot{"location": "delhi"}
    - action_check_location
    - slot{"location_match": "one"}
    - utter_searching
    - action_restaurant
    - slot{"location": "delhi"}
    - utter_ask_for_email_to_send
* send_email{"email": "shashit95@gmail.com"}
    - slot{"email": "shashit95@gmail.com"}
    - action_send_email
    - utter_email_sent
    - action_restart

## interactive_story_1
* greet
    - utter_greet
* restaurant_search{"cuisine": "chinese", "budget": "2000"}
    - slot{"cuisine": "chinese"}
    - slot{"budget": "2000"}
    - utter_ask_location
* restaurant_search{"location": "delhi"}
    - slot{"location": "delhi"}
    - action_check_location
    - slot{"location_match": "one"}
    - utter_searching
    - action_restaurant
    - slot{"location": "delhi"}
    - utter_ask_for_email_to_send
* send_email{"email": "shashit95@gmail.com"}
    - slot{"email": "shashit95@gmail.com"}
    - action_send_email
    - utter_email_sent
    - action_restart

## interactive_story_1
* greet
    - utter_greet
* restaurant_search{"cuisine": "chinese", "budget": "2000"}
    - slot{"cuisine": "chinese"}
    - slot{"budget": "2000"}
    - utter_ask_location
* restaurant_search{"location": "delhi"}
    - slot{"location": "delhi"}
    - action_check_location
    - slot{"location_match": "one"}
    - utter_searching
    - action_restaurant
    - slot{"location": "delhi"}
    - utter_ask_for_email_to_send
* send_email{"email": "shashit95@gmail.com"}
    - slot{"email": "shashit95@gmail.com"}
    - action_send_email
    - utter_email_sent
    - action_restart

## interactive_story_1
* greet
    - utter_greet
* restaurant_search{"cuisine": "chinese", "budget": "2000"}
    - slot{"cuisine": "chinese"}
    - slot{"budget": "2000"}
    - utter_ask_location
* restaurant_search{"location": "delhi"}
    - slot{"location": "delhi"}
    - action_check_location
    - slot{"location_match": "one"}
    - utter_searching
    - action_restaurant
    - slot{"location": "delhi"}
    - utter_ask_for_email_to_send
* send_email{"email": "shashit95@gmail.com"}
    - slot{"email": "shashit95@gmail.com"}
    - action_send_email
    - utter_email_sent
    - action_restart

## interactive_story_1
* greet
    - utter_greet
* restaurant_search{"cuisine": "chinese", "budget": "2000"}
    - slot{"cuisine": "chinese"}
    - slot{"budget": "2000"}
    - utter_ask_location
* restaurant_search{"location": "delhi"}
    - slot{"location": "delhi"}
    - action_check_location
    - slot{"location_match": "one"}
    - utter_searching
    - action_restaurant
    - slot{"location": "delhi"}
    - utter_ask_for_email_to_send
* send_email{"email": "shashit95@gmail.com"}
    - slot{"email": "shashit95@gmail.com"}
    - action_send_email
    - utter_email_sent
    - action_restart

## interactive_story_1
* greet
    - utter_greet
* restaurant_search{"cuisine": "chinese", "budget": "2000"}
    - slot{"cuisine": "chinese"}
    - slot{"budget": "2000"}
    - utter_ask_location
* restaurant_search{"location": "delhi"}
    - slot{"location": "delhi"}
    - action_check_location
    - slot{"location_match": "one"}
    - utter_searching
    - action_restaurant
    - slot{"location": "delhi"}
    - utter_ask_for_email_to_send
* send_email{"email": "shashit95@gmail.com"}
    - slot{"email": "shashit95@gmail.com"}
    - action_send_email
    - utter_email_sent
    - action_restart

## interactive_story_1
* greet
    - utter_greet
* restaurant_search{"cuisine": "chinese", "budget": "2000"}
    - slot{"cuisine": "chinese"}
    - slot{"budget": "2000"}
    - utter_ask_location
* restaurant_search{"location": "delhi"}
    - slot{"location": "delhi"}
    - action_check_location
    - slot{"location_match": "one"}
    - utter_searching
    - action_restaurant
    - slot{"location": "delhi"}
    - utter_ask_for_email_to_send
* send_email{"email": "shashit95@gmail.com"}
    - slot{"email": "shashit95@gmail.com"}
    - action_send_email
    - utter_email_sent
    - action_restart

## interactive_story_1
* greet
    - utter_greet
* restaurant_search{"cuisine": "chinese", "budget": "2000"}
    - slot{"cuisine": "chinese"}
    - slot{"budget": "2000"}
    - utter_ask_location
* restaurant_search{"location": "delhi"}
    - slot{"location": "delhi"}
    - action_check_location
    - slot{"location_match": "one"}
    - utter_searching
    - action_restaurant
    - slot{"location": "delhi"}
    - utter_ask_for_email_to_send
* send_email{"email": "shashit95@gmail.com"}
    - slot{"email": "shashit95@gmail.com"}
    - action_send_email
    - utter_email_sent
    - action_restart

## interactive_story_1
* greet
    - utter_greet
* restaurant_search{"cuisine": "chinese", "budget": "2000"}
    - slot{"cuisine": "chinese"}
    - slot{"budget": "2000"}
    - utter_ask_location
* restaurant_search{"location": "delhi"}
    - slot{"location": "delhi"}
    - action_check_location
    - slot{"location_match": "one"}
    - utter_searching
    - action_restaurant
    - slot{"location": "delhi"}
    - utter_ask_for_email_to_send
* send_email{"email": "shashit95@gmail.com"}
    - slot{"email": "shashit95@gmail.com"}
    - action_send_email
    - utter_email_sent
    - action_restart

## interactive_story_1
* greet
    - utter_greet
* restaurant_search{"cuisine": "chinese", "budget": "2000"}
    - slot{"cuisine": "chinese"}
    - slot{"budget": "2000"}
    - utter_ask_location
* restaurant_search{"location": "delhi"}
    - slot{"location": "delhi"}
    - action_check_location
    - slot{"location_match": "one"}
    - utter_searching
    - action_restaurant
    - slot{"location": "delhi"}
    - utter_ask_for_email_to_send
* send_email{"email": "shashit95@gmail.com"}
    - slot{"email": "shashit95@gmail.com"}
    - action_send_email
    - utter_email_sent
    - action_restart

## interactive_story_1
* greet
    - utter_greet
* restaurant_search{"cuisine": "chinese", "budget": "2000"}
    - slot{"cuisine": "chinese"}
    - slot{"budget": "2000"}
    - utter_ask_location
* restaurant_search{"location": "delhi"}
    - slot{"location": "delhi"}
    - action_check_location
    - slot{"location_match": "one"}
    - utter_searching
    - action_restaurant
    - slot{"location": "delhi"}
    - utter_ask_for_email_to_send
* send_email{"email": "shashit95@gmail.com"}
    - slot{"email": "shashit95@gmail.com"}
    - action_send_email
    - utter_email_sent
    - action_restart

## interactive_story_1
* greet
    - utter_greet
* restaurant_search{"cuisine": "chinese", "budget": "2000"}
    - slot{"cuisine": "chinese"}
    - slot{"budget": "2000"}
    - utter_ask_location
* restaurant_search{"location": "delhi"}
    - slot{"location": "delhi"}
    - action_check_location
    - slot{"location_match": "one"}
    - utter_searching
    - action_restaurant
    - slot{"location": "delhi"}
    - utter_ask_for_email_to_send
* send_email{"email": "shashit95@gmail.com"}
    - slot{"email": "shashit95@gmail.com"}
    - action_send_email
    - utter_email_sent
    - action_restart

## interactive_story_1
* greet
    - utter_greet
* restaurant_search{"cuisine": "chinese", "budget": "2000"}
    - slot{"cuisine": "chinese"}
    - slot{"budget": "2000"}
    - utter_ask_location
* restaurant_search{"location": "delhi"}
    - slot{"location": "delhi"}
    - action_check_location
    - slot{"location_match": "one"}
    - utter_searching
    - action_restaurant
    - slot{"location": "delhi"}
    - utter_ask_for_email_to_send
* send_email{"email": "shashit95@gmail.com"}
    - slot{"email": "shashit95@gmail.com"}
    - action_send_email
    - utter_email_sent
    - action_restart

## interactive_story_1
* greet
    - utter_greet
* restaurant_search{"cuisine": "chinese", "budget": "2000"}
    - slot{"cuisine": "chinese"}
    - slot{"budget": "2000"}
    - utter_ask_location
* restaurant_search{"location": "delhi"}
    - slot{"location": "delhi"}
    - action_check_location
    - slot{"location_match": "one"}
    - utter_searching
    - action_restaurant
    - slot{"location": "delhi"}
    - utter_ask_for_email_to_send
* send_email{"email": "shashit95@gmail.com"}
    - slot{"email": "shashit95@gmail.com"}
    - action_send_email
    - utter_email_sent
    - action_restart

## interactive_story_1
* greet
    - utter_greet
* restaurant_search{"cuisine": "chinese", "budget": "2000"}
    - slot{"cuisine": "chinese"}
    - slot{"budget": "2000"}
    - utter_ask_location
* restaurant_search{"location": "delhi"}
    - slot{"location": "delhi"}
    - action_check_location
    - slot{"location_match": "one"}
    - utter_searching
    - action_restaurant
    - slot{"location": "delhi"}
    - utter_ask_for_email_to_send
* send_email{"email": "shashit95@gmail.com"}
    - slot{"email": "shashit95@gmail.com"}
    - action_send_email
    - utter_email_sent
    - action_restart

## interactive_story_1
* greet
    - utter_greet
* restaurant_search{"cuisine": "chinese", "budget": "2000"}
    - slot{"cuisine": "chinese"}
    - slot{"budget": "2000"}
    - utter_ask_location
* restaurant_search{"location": "delhi"}
    - slot{"location": "delhi"}
    - action_check_location
    - slot{"location_match": "one"}
    - utter_searching
    - action_restaurant
    - slot{"location": "delhi"}
    - utter_ask_for_email_to_send
* send_email{"email": "shashit95@gmail.com"}
    - slot{"email": "shashit95@gmail.com"}
    - action_send_email
    - utter_email_sent
    - action_restart

## interactive_story_1
* greet
    - utter_greet
* restaurant_search{"cuisine": "chinese", "budget": "2000"}
    - slot{"cuisine": "chinese"}
    - slot{"budget": "2000"}
    - utter_ask_location
* restaurant_search{"location": "delhi"}
    - slot{"location": "delhi"}
    - action_check_location
    - slot{"location_match": "one"}
    - utter_searching
    - action_restaurant
    - slot{"location": "delhi"}
    - utter_ask_for_email_to_send
* send_email{"email": "shashit95@gmail.com"}
    - slot{"email": "shashit95@gmail.com"}
    - action_send_email
    - utter_email_sent
    - action_restart

## interactive_story_1
* greet
    - utter_greet
* restaurant_search
    - utter_ask_location
* restaurant_search{"location": "Kochi"}
    - slot{"location": "Kochi"}
    - action_check_location
    - slot{"location_match": "one"}
    - utter_ask_cuisine
* restaurant_search{"cuisine": "Mexican"}
    - slot{"cuisine": "Mexican"}
    - utter_ask_budget
* restaurant_search{"budget": "2"}
    - slot{"budget": "2"}
    - utter_searching
    - action_restaurant
    - slot{"location": "Kochi"}
    - utter_ask_for_email_to_send
* send_email{"email": "shashit95@gmail.com"}
    - slot{"email": "shashit95@gmail.com"}
    - action_send_email
    - reset_slots
    - utter_email_sent
    - action_restart

## interactive_story_1
* greet
    - utter_greet
* restaurant_search{"location": "nagpur"}
    - slot{"location": "nagpur"}
    - action_check_location
    - slot{"location_match": "one"}
    - utter_ask_cuisine
* restaurant_search{"cuisine": "South Indian"}
    - slot{"cuisine": "South Indian"}
    - utter_ask_budget
* restaurant_search{"budget": "2"}
    - slot{"budget": "2"}
    - utter_searching
    - action_restaurant
    - slot{"location": "nagpur"}
    - utter_ask_for_email_to_send
* deny
    - utter_no_email_sent
    - action_restart

## interactive_story_1
* greet
    - utter_greet
* restaurant_search{"cuisine": "italian", "location": "pune"}
    - slot{"cuisine": "italian"}
    - slot{"location": "pune"}
    - action_check_location
    - slot{"location_match": "one"}
    - utter_ask_budget
* restaurant_search{"budget": "1000"}
    - slot{"budget": "1000"}
    - utter_searching
    - action_restaurant
    - slot{"location": "pune"}
    - utter_ask_for_email_to_send
* restaurant_search{"email": "ayushi.dreambig@gmail.com"}
    - slot{"email": "ayushi.dreambig@gmail.com"}
    - action_send_email
    - reset_slots
    - utter_email_sent
    - action_restart

## interactive_story_1
* greet
    - utter_greet
* restaurant_search
    - utter_ask_location
* restaurant_search{"location": "amritsar"}
    - slot{"location": "amritsar"}
    - action_check_location
    - slot{"location_match": "one"}
    - utter_ask_cuisine
* restaurant_search{"cuisine": "Italian"}
    - slot{"cuisine": "Italian"}
    - utter_ask_budget
* restaurant_search{"budget": "1"}
    - slot{"budget": "1"}
    - utter_searching
    - action_restaurant
    - slot{"location": "amritsar"}
    - utter_ask_for_email_to_send
* restaurant_search{"email": "ayushi.dreambig@gmail.com"}
    - slot{"email": "ayushi.dreambig@gmail.com"}
    - action_send_email
    - reset_slots
    - utter_email_sent
* affirm
    - utter_goodbye
    - action_restart
