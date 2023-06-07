# ATOM-ARCHIVE

Artifacts from our paper [ATOM](https://petsymposium.org/2022/paperlist.php)

## Structure

```
ATOM
│
└───README.md
│   │    
│   │
└───H1
│   │   Ads (~1.5 GB)
│   │   Runs (~1.0 GB)
│   │   Personas
│   │   Config
│   │   hash-label.json
│   │
└───H2
│   │   Ads (~2.0 GB)
│   │   Runs (~2.0 GB)
│   │   Org-Filter-Rules
│   │   Config
│   │   hash-label.json
```

## Description of Folders

### H1

- Ads: Unique Ads from our first instrumentation. Which determines if characteristics of ad creatives are dependent on user interest (Section 3)
- Runs: Details of each ad gathered in this run. Run 1 and 2 were test runs)
- Personas: Sites used for each user interest
- Config: OpenWPM configuration for this phase
- hash-label.json: annotated unique ad creatives with meta data

### H2

- Ads: Unique Ads from our second instrumentation. Which determines relationships between trackers and advertisers (Section 4)
- Runs: Details of each ad gathered in this run. Run 1,2,3 and 4 were test runs and are not included here)
- Org-Filter-Rules: Rules used to block an organization
- Config: OpenWPM configuration for this phase
- hash-label.json: annotated unique ad creatives with meta data

#### Warnings

- As we trained adult personas, you can expect to see adult images in the ads dataset.

Citation
--------

    @inproceedings{musa2022pets,
        author    = "Maaz Bin Musa and Rishab Nithyanand",
        title     = "{ATOM: Ad-network Tomography; A Generalizable Technique for Inferring Tracker-Advertiser Data Sharing in the Online Behavioral Advertising Ecosystem}",
        booktitle = {Proceedings of PoPETs 2022},
        year      = "2022",
    }
    