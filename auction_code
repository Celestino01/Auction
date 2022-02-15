from replit import clear

auction_dictionary = {}

def auction(name, bid):
  auction_dictionary[name] = bid

def winner():
  bid_amount = 0
  winners_name = ""
  for key in auction_dictionary:
    if auction_dictionary[key] > bid_amount:
      bid_amount = auction_dictionary[key]
      winners_name = key
  print(f"The winner is {winners_name} with a bid of ${bid_amount}")
  

any_biders = "yes"

print("Welcome to the secret auction program")

while any_biders == "yes":
  name = input("What is your name? ")
  bid = int(input("What's your bid? $"))
  auction(name, bid)
  any_biders = input("Are their any other biders? Type 'yes' or 'no'").lower()


  if any_biders == "no":
    any_biders = "no"
  else:
    clear()

winner()
