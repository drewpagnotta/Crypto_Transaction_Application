# Ethereum Transaction Application

### Objective: To successfully send an ETH transaction on the blockchain.

Using the Ethereum blockchain platform Ganache, we verify a transaction of ETH was sent and verified on the blockchain when selecting and paying a FinTech professional.

---

## Imports

<img width="395" alt="Screen Shot 2022-11-15 at 2 26 43 PM" src="https://user-images.githubusercontent.com/108194033/202028693-dfa10520-a1bc-45eb-b748-4775b0044b92.png">

Through a separate Python file, we have three functions defined...

```
generate_account()
get_balance(w3, address)
send_transaction(w3, account, to, wage)
```

...and we import those functions into our *crypto_wallet.py* application file:

<img width="535" alt="Screen Shot 2022-11-15 at 2 31 17 PM" src="https://user-images.githubusercontent.com/108194033/202029409-c3d93e9b-b222-420b-bcf2-f12ae253400d.png">

---

## Testing the Application

Main Page

<img width="1673" alt="Screen Shot 2022-11-15 at 2 07 59 PM" src="https://user-images.githubusercontent.com/108194033/202029690-22e311f7-14e4-4631-9643-4aaf2ff10dd4.png">

Select FinTech Professional & Amount of Hours (to be paid in ETH)

<img width="328" alt="Screen Shot 2022-11-15 at 2 13 08 PM" src="https://user-images.githubusercontent.com/108194033/202029823-bb01c270-6786-4f72-a46e-9da06f986a5a.png">

Execute & Verify Transaction

<img width="324" alt="Screen Shot 2022-11-15 at 2 18 24 PM" src="https://user-images.githubusercontent.com/108194033/202029999-37e664c4-e495-4239-a026-9fae5f76197f.png">

Verify Transaction Hash and ETH Balance on Ganache

<img width="1193" alt="Screen Shot 2022-11-15 at 2 37 31 PM" src="https://user-images.githubusercontent.com/108194033/202030443-548ac882-2e3a-402c-b7cb-34b60ad08269.png"><img width="1196" alt="Screen Shot 2022-11-15 at 2 19 03 PM" src="https://user-images.githubusercontent.com/108194033/202030387-6172f499-a184-4404-bb96-f3a2ceb5db21.png">

