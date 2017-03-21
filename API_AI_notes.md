Please refer to the https://docs.api.ai/docs/key-concepts for detailed info about key concepts.
## Intents
1. Find Domain
2. Find Symptom
## entities
* __Domains__:
  1. Refrigeration: Refrigeration, Fridge, Freezer  
  2. Washer: Washer, Washing Machine  
  3. Dryer: Dryer  
  4. Dish: Dish Washer  
  5. Cooking: Range, Oven, Wall-Oven, Microwave  
* __Symptoms__:   
it is better to define Domain specified symptoms.
Example: Washer_Symptoms: Leaking.
Frige, Washer, Dryer, Dish-washer all can leak.
So the leaking symptom makes sense in the Domain context.
## Training
1. Upload Examples: and tag them using the provided Entities.
2. The bot will save the conversation whether recognized or not in Trainig -> History.  
  tag the unsuccessful interactions to help the Machine learn the new patterns.
