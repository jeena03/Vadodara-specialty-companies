# 1000 Company ICP Proposal
---
## Objective

The goal is to build a list of 1000 high-quality ICP-qualified companies within one month. These companies should not be random names but properly verified manufacturers that meet all six criteria.

The focus is on quality, not volume.

## Sourcing the Initial Universe

I would not start directly with scoring. First, I would build a large pool of companies.

The initial universe will come from multiple sources:

- DSIR R&D company list to identify technically strong companies  
- Expo exhibitor lists such as CPHI, BioAsia, and industrial expos  
- BSE SME and NSE Emerge listed companies for reliable data  
- USFDA, EU-GMP, and WHO-approved facility lists  
- Industry association directories  
- MCA data using NIC codes and city filters  
- LinkedIn search to identify companies through founders and leadership  

After combining and removing duplicates, the target is to build a pool of around 3500 to 4000 companies.

## Automating the Qualification Step

Each company will go through a semi-automated pipeline.

First, company websites will be scraped. Pages like homepage, about, products, leadership, and careers will be collected.

Then AI will be used to evaluate each company across the six criteria.

The process will be:

- Scrape website content  
- Send structured data to an AI model  
- Get scores for C1 to C6 with short evidence  
- Store results in a sheet  

Before sending to AI, some companies will be automatically rejected. For example, companies without websites, trading firms, or those clearly outside the required size range.

This reduces time and improves accuracy.

## Quality Control

AI alone is not enough. There will be false positives.

So I will use a two-step quality check.

First, automated flags  
Companies with weak evidence, outdated activity, or unclear differentiation will be flagged  

Second, manual review  
All flagged companies will be reviewed manually  
Some strong companies will also be randomly checked  

This ensures that the final list is reliable and not inflated by incorrect AI judgments.

## Weekly Plan

### Week 1

- Focus on sourcing  
- Build a list of 3500 to 4000 companies  
- Clean and remove duplicates  
- Find missing websites  

### Week 2

- Build and test scraping system  
- Start collecting website data  
- Run first round of AI scoring  

### Week 3

- Complete scoring for all companies  
- Re-evaluate borderline cases  
- Start quality checks  

### Week 4

- Finish manual review  
- Finalize top 1000 companies  
- Prepare final CSV and documentation  

## Expected Yield

From my experience, only around 25 to 30 percent of companies will qualify.

From 3500 to 4000 companies:  

- Around 2000 will pass basic filtering  
- Around 1200 to 1400 will pass AI scoring  
- Final 1000 will be selected after quality checks  

## Final Output

The final result will include:

- A CSV file with 1000 companies  
- Each company will have scores for all six criteria with evidence  
- A short methodology explanation  
- A clean and structured dataset ready for use  

## Key Approach

The approach is simple.

- Build a large pool  
- Filter fast  
- Use AI to speed up scoring  
- Verify manually where needed  

The goal is to balance speed with accuracy and ensure that the final list is genuinely useful.
