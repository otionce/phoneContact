# phoneContact
//Contact Manager such as those found on smartphones
//Skeleton code was given by instructor, J. Corless, September 2016


PhoneNumberList.java makes use of an array to store contact info using the following functions:
  - public PhoneNumber get(int positionOfNumber);
  - public void remove(int indexOfPhoneNumber);
  - public int size();
  - public void add(PhoneNumber numberToAdd);
  - public int find(PhoneNumber numberToFind);

Contact.java is a contact that stores a PhoneNumberList of multiple phone numbers for a contact with a name using the following functions:
  - public Contact(String name);
  - public Contact(String name, PhoneNumber number);
  - public String getName();
  - public void setName(String nameToSet);
  - public void addNumber(PhoneNumber toAdd);
  - public void removeNumber(PhoneNumber phoneNumberToRemove);
  - public int getNumberCount();
  - public PhoneNumber getNumber(PhoneNumber posOfPhoneNumber);
  - public String toString();
