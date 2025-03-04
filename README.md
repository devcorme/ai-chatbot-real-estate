## Artifact for Real Estate Agent  

The artifact for the real estate agent can be found at:  

/artifacts/real-estate


It consists of three main components:  
- **Image Slideshow**
- **Map**
- **Listing Page** 

All three components are gathered into one via the **client file**.  

---

## Tools  

Tools can be found in:  

/lib/ai/tools


There are two implemented tools:  
1. **real-estate-review** – Provides listing history based on the listing ID, including possible changes.  
2. **real-estate-offer** – Finds the three best listings.

Both tools target the same endpoint since the implemented agent has both functionalities.  

---

## Chat Preview  

The preview displayed in the chat can be found at:  

/components/real-estate-preview

_Note 1: Prompts should be considered since some changes are made, especially the artifacts prompt._
_Note 2: It is important to check the description of the create-document tool (aka "tunneling" solution)_
