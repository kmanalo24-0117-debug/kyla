def percentage(value, total):
    return (value / total) * 100
    
def main():
   while True:
      value = float(input("Enter the value:"))
      total = float(input("Enter the total:"))
   
      percent = percentage(value, total)
 
      print(f"{percent:.2f}% of {total:.2f} is {value:.2f}")

      choice = input ("\ntry another [y|n]? ").lower()
      if choice != 'y':
       Break

if __name__ == " __main__":
  main()
