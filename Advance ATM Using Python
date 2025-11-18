{
 "cells": [
  {
   "cell_type": "code",
   "execution_count": 1,
   "id": "586e19b9-4381-4b86-bf2a-342001c10dab",
   "metadata": {},
   "outputs": [
    {
     "name": "stdout",
     "output_type": "stream",
     "text": [
      "Welcome to Navneet ATM\n",
      "Select Language:\n",
      "1. English\n",
      "2. Hindi\n"
     ]
    },
    {
     "name": "stdin",
     "output_type": "stream",
     "text": [
      "Enter 1 or 2:  1\n",
      "Enter 4-digit PIN:  1234\n"
     ]
    },
    {
     "name": "stdout",
     "output_type": "stream",
     "text": [
      "PIN Verified \n",
      "Menu:\n",
      "1. Balance Check\n",
      "2. Deposit\n",
      "3. Withdraw\n"
     ]
    },
    {
     "name": "stdin",
     "output_type": "stream",
     "text": [
      "Enter your choice (1/2/3):  1\n"
     ]
    },
    {
     "name": "stdout",
     "output_type": "stream",
     "text": [
      "Your Balance = 5000\n"
     ]
    }
   ],
   "source": [
    "# correct_pin = \"1234\"\n",
    "balance = 5000\n",
    "attempts = 0\n",
    "\n",
    "print(\"Welcome to Navneet ATM\")\n",
    "print(\"Select Language:\")\n",
    "print(\"1. English\")\n",
    "print(\"2. Hindi\")\n",
    "language = input(\"Enter 1 or 2: \")\n",
    "\n",
    "if language != \"1\":\n",
    "    print(\"Sorry currently only English language is available.\")\n",
    "    \n",
    "while attempts < 3:\n",
    "    pin = input(\"Enter 4-digit PIN: \")\n",
    "\n",
    "    if len(pin) != 4:\n",
    "        print(\"PIN must be exactly 4 digits\")\n",
    "        continue  \n",
    "    if pin == correct_pin:\n",
    "        print(\"PIN Verified \")\n",
    "        print(\"Menu:\")\n",
    "        print(\"1. Balance Check\")\n",
    "        print(\"2. Deposit\")\n",
    "        print(\"3. Withdraw\")\n",
    "\n",
    "        choice = input(\"Enter your choice (1/2/3): \")\n",
    "\n",
    "        if choice == \"1\":\n",
    "            print(\"Your Balance =\", balance)\n",
    "\n",
    "        elif choice == \"2\":\n",
    "            amount = int(input(\"Enter Amount to Deposit: \"))\n",
    "            balance = balance + amount\n",
    "            print(\"Deposit Successful \")\n",
    "            print(\"Updated Balance =\", balance)\n",
    "\n",
    "        elif choice == \"3\":\n",
    "            amount = int(input(\"Enter Amount to Withdraw: \"))\n",
    "            if amount > balance:\n",
    "                print(\"Not Enough Balance \")\n",
    "            else:\n",
    "                balance = balance - amount\n",
    "                print(\"Withdraw Successful \")\n",
    "                print(\"Updated Balance =\", balance)\n",
    "\n",
    "        else:\n",
    "            print(\"Invalid Option \")\n",
    "        break\n",
    "\n",
    "    else:\n",
    "        attempts += 1\n",
    "        print(\"Incorrect PIN \")\n",
    "\n",
    "\n",
    "if attempts == 3:\n",
    "    print(\"3 Wrong Attempts \")\n",
    "    print(\"Your ATM Card is Locked for 24 Hours \")"
   ]
  },
  {
   "cell_type": "code",
   "execution_count": null,
   "id": "047772cb-0b28-4544-bd15-b42cdbaaa04e",
   "metadata": {},
   "outputs": [],
   "source": []
  },
  {
   "cell_type": "code",
   "execution_count": null,
   "id": "37879dec-3924-4b6d-8479-ed3300fa0e9d",
   "metadata": {},
   "outputs": [],
   "source": []
  }
 ],
 "metadata": {
  "kernelspec": {
   "display_name": "Python 3 (ipykernel)",
   "language": "python",
   "name": "python3"
  },
  "language_info": {
   "codemirror_mode": {
    "name": "ipython",
    "version": 3
   },
   "file_extension": ".py",
   "mimetype": "text/x-python",
   "name": "python",
   "nbconvert_exporter": "python",
   "pygments_lexer": "ipython3",
   "version": "3.13.5"
  }
 },
 "nbformat": 4,
 "nbformat_minor": 5
}
