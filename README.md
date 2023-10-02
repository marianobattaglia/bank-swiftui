# bank-swiftui

Application to manage different bank accounts made with SwiftUI and MVVM design pattern.

The application works with a backend made with express and deployed in Glitch https://bloom-outgoing-balmoral.glitch.me/

### Endpoints

| Endpoint         | Type   | Body                                                  | Parameters | Description               |
|------------------|--------|-------------------------------------------------------|------------|---------------------------|
| api/accounts     | GET    | -                                                     | -          | Get account list          |
| api/accounts     | POST   | name: String accountType: String balance: Int         | -          | Create new account        |
| api/accounts/:id | DELETE | -                                                     | id: UUID   | Delete account by ID      |
| api/transfer     | POST   | accountFromId: String accountToId: String amount: Int | -          | Transfer between accounts |


# Views

### AccountSummary

<div>
	<p align= 'center'>
		<img src="https://github.com/marianobattaglia/bank-swiftui/assets/94753551/59fd54d2-33a8-4201-813e-be1db51061b3" width="250">
	</p>
</div>

### AddAccount

<div>
	<p align= 'center'>
		<img src="https://github.com/marianobattaglia/bank-swiftui/assets/94753551/4ced8b8e-42b4-4e51-9717-63c4a5ec32c7" width="250">
	</p>
</div>

### TransferFunds

<div>
	<p align= 'center'>
		<img src="https://github.com/marianobattaglia/bank-swiftui/assets/94753551/520184ee-8e73-4008-ad03-f00a90712a70" width="250">
	</p>
</div>
