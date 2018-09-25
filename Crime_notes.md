## Crime ontology notes (Classes, Properties, Resources)

Area           | Type  | Component name      | Super | Base ontology | Notes
-------------- | ----- | ------------------- | ----- | ------------- | -----
Bio            | Class | Birth               | | |
Bio            | Class | Death               | | |
Bio            | Class | Disease             | | |
Bio            | Class | Education           | | |
Bio            | Class | Person              | | |
Bio            | Class | Profession          | | |
Bio            | Class | Religion            | | |
Bio            | Pred  | isBioChildOf        | | |
Bio            | Pred  | isBioParentOf       | | |
---
Bomb           | Class | BombConventional    | | |
Bomb           | Class | BombNuclear         | | |
---
Business       | Class | Company             | | |
Business       | Class | ContractParty       | | |
Business       | Class | Organization        | | | E.g., Political,Religion,Social
---
Chemical       | Class | Chemical            | | |
---
Communication  | Class | CellPhone           | | | 
Communication  | Class | Language            | | |
Communication  | Class | Message             | | |
Communication  | Class | PhoneCall           | | |
Communication  | Class | WrittenMessage      | | |
---
Finance        | Class | BankAccount         | | |
Finance        | Class | BribeActivity       | | |
Finance        | Class | Currency            | | |
Finance        | Class | EFT                 | | |
Finance        | Class | FinancialDerivative | | |
Finance        | Class | FinancialFraudType  | | |
Finance        | Class | Money               | | |
Finance        | Class | Stock               | | |
---
Geo            | Class | Address             | | |
Geo            | Class | Building            | | |
Geo            | Class | City                | | |
Geo            | Class | Country             | | |
Geo            | Class | Location            | | |
---
Law            | Class | Arrest              | | |
Law            | Class | Case                | | |
Law            | Class | Contract            | | |
Law            | Class | CriminalCharge      | | |
Law            | Class | Identification      | | |
Law            | Class | Jurisdiction        | | |
Law            | Class | LegalClaim          | | | 
Law            | Class | TrialActivity       | | |
Law            | Class | WitnessActivity     | | |
---
Time           | Class | DateTime            | | |
---
Travel         | Class | Airplane            | | |
Travel         | Class | Boat                | | |
Travel         | Class | Car                 | | |
Travel         | Class | Passport            | | |
Travel         | Class | TravelActivity      | | |
Travel         | Prop  | transportationMode  | | |
---
Transportation | Class | Vehicle             | | |
---
Terrorism      | Class | HijackActivity      | | |
---
Weapon         | Class | Bomb                | | |
Weapon         | Class | Firearm             | | |
Weapon         | Class | Knife               | | |
Weapon         | Class | Weapon              | | |

