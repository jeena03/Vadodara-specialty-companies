# 1000 Company ICP Proposal

---

## Objective

The goal is to build a list of 1000 high-quality ICP-qualified companies within one month. These companies should not be random names but properly verified manufacturers that meet all six criteria.

The focus is on quality, not volume.

## Sourcing the Initial Universe

I would not start directly with scoring. First, I would build a large pool of companies.

The initial universe will come from multiple sources:

1. DSIR R&D company list to identify technically strong companies  
2. Expo exhibitor lists such as CPHI, BioAsia, and industrial expos  
3. BSE SME and NSE Emerge listed companies for reliable data  
4. USFDA, EU-GMP, and WHO-approved facility lists  
5. Industry association directories  
6. MCA data using NIC codes and city filters  
7. LinkedIn search to identify companies through founders and leadership  

After combining and removing duplicates, the target is to build a pool of around 3500 to 4000 companies.

## Automating the Qualification Step

Each company will go through a semi-automated pipeline.

First, company websites will be scraped. Pages like homepage, about, products, leadership, and careers will be collected.

Then AI will be used to evaluate each company across the six criteria.

The process will be:

1. Scrape website content  
2. Send structured data to an AI model  
3. Get scores for C1 to C6 with short evidence  
4. Store results in a sheet  

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

1. Focus on sourcing  
2. Build a list of 3500 to 4000 companies  
3. Clean and remove duplicates  
4. Find missing websites  

### Week 2

1. Build and test scraping system  
2. Start collecting website data  
3. Run first round of AI scoring  

### Week 3

1. Complete scoring for all companies  
2. Re-evaluate borderline cases  
3. Start quality checks  

### Week 4

1. Finish manual review  
2. Finalize top 1000 companies  
3. Prepare final CSV and documentation  

## Expected Yield

From my experience, only around 25 to 30 percent of companies will qualify.

From 3500 to 4000 companies:  

1. Around 2000 will pass basic filtering  
2. Around 1200 to 1400 will pass AI scoring  
3. Final 1000 will be selected after quality checks  

## Final Output

The final result will include:

1. A CSV file with 1000 companies  
2. Each company will have scores for all six criteria with evidence  
3. A short methodology explanation  
4. A clean and structured dataset ready for use  

## Key Approach

The approach is simple.

1. Build a large pool  
2. Filter fast  
3. Use AI to speed up scoring  
4. Verify manually where needed  

The goal is to balance speed with accuracy and ensure that the final list is genuinely useful.
