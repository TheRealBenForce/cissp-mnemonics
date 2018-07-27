# Domain 1: Security and Risk Management

## Risk Management

SLE = AV * EF
 - Single Loss Expectancy (SLE) - Negative impact for one-time occurrence
 - Asset Value (AV)
 - Exposure Factor (EF) - If a flood will damage 40% of your data center, EF is 40%

ARO
 - Annual Rate of Occurance

ALE = ARO * SLE
 - :beer: = :heart_eyes: (get it?)
  - Ale makes arousal
 - Annual Loss Expectancy = Rate of Occurrence - Single Loss Expectancy

## Threat Modeling

STRIDE - Microsoft threat modeling tool
- **S** poofing
- **T** ampering
- **R** epudiation - attacker can deny participation
- **I** nformation disclosure
- **D** enial of service
- **E** levation of privilege

## Control Types
PTA keeps the children safe!
* **P** hysical - Tangible. Locks, guards, alligator moats, etc.
* **T** echincal/Logical - Automated or electronic systems.
* **A** dministrative - Policy, signage.

## Due Care vs Due Diligence
Imagine you have a pool. To protect children and animals from drowning in your pool, you exercise due care by building a fence around the pool. Regularly checking the fence for vulnerabilities and correcting them demonstrates due diligence.

Due Care - A vendor engaging in a reasonable and expected manner for the circumstance
Due Diligence - Demonstrates due care

# Domain 3: Security Engineering
## Security Models

## Brewer-Nash
Brewer-Nash is also known as "The Chinese Wall" and protects against conflict of interest. Remember Chinese "brew" tea. :tea:

## Simple Security vs \*-Security

You must read before you can write. So reading is "simpler" than writing. This makes reading the simple security model and writing the \*-security model.

## Integrity vs Confidentiality models
* Integrity Models have the letter "I" in them.
* Bell LaPadula and Biba -  Since Biba has an "I" I it, it is integrity. The two are opposite so Bell is confidentiality. For some something confidential you don't want a subject reading up above their security. So Bell has a no read up property.

# Domain 4: Communications & Network Security
## DES Modes of Operation
Most important thing here is remember strength from weakest to strongest. No clear mneumonic to do this, except remember the first and the last. The center 3 are alphabetical by name and/or abbreviation.
1. ECB - Electronic Code Block (also the only one that doesn't support an initialization vector)
2. CBC - Cipher Block Chaining
3. CFB - Cipher Feedback
4. OFB - Output Feedback Mode
5. CTR - Counter


## Cloud Computing Operating Model
IaaS, PaaS, SaaS - [Remember Pizza as a Service](https://medium.com/@pkerrison/pizza-as-a-service-2-0-5085cd4c365e)

# Domain 7: Security operations
## Fire Classes and Extinguisher Types
|Type |Mneumonic    |Description                  |
|-----|-------------|-----------------------------|
|A    |Ash          |Ordinary solid combustibles  |
|B    |Boil, Bubble |Flammable liquids and gasses |
|C    |Circuits     |Electrical equipment         |
|D    |Dent         |Combustible metals           |
|K    |Kitchen      |Oils and fats                |

# Domain8: Software Development Security
## Ring computing model

Remember "Zero KODU"

|Layer  |Purpose              |
|---    |---                  |
|0   	  |**K**ernal           |
|1   	  |**O**perating System |
|2   	  |**D**rivers          |
|3   	  |**U**ser             |
