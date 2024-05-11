# EDM24_SRL-detectors-for-think-aloud

In this study, we experimented with two LLMs (Universal Sentence Encod-ers and OpenAI’s text-embedding-3-small) to predict four SRL categories (processing information, planning, enacting, and realizing errors) in students' verbalizations, collected from three intelligent tutoring systems, covering stoichiometry chemistry and formal logic.

## Citation

Zhang, J., Borchers, C., Aleven, V., & Baker, R. S. (2024). Using Large Language Models to Detect Self-Regulated Learning in Think-Aloud Protocols. Proceedings of the 17th International Conference on Educational Data Mining (EDM). Atlanta, GA, USA.

```
@inproceedings{zhang2024using,
  title={Using Large Language Models to Detect Self-Regulated Learning in Think-Aloud Protocols},
  author={Zhang, J. and Borchers, C. and Aleven, V. and Baker, R. S.},
  booktitle={Proceedings of the 17th International Conference on Educational Data Mining (EDM)},
  location={Atlanta, GA, USA},
  year={2024}
}
```

## Preprint

https://osf.io/preprints/edarxiv/hrtz6

## Data availability and setup

First, open the two CMU Datashop dataset webpages in your browser.

https://pslcdatashop.web.cmu.edu/DatasetInfo?datasetId=5820
<br>
https://pslcdatashop.web.cmu.edu/DatasetInfo?datasetId=5371

To access the datasets, you will need to request access with an account on DataShop. You can create an account using your Google or GitHub account, whichever is easiest.

Once you have created an account, navigate back to the dataset webpages and click on the button `Request Access`. Provide your reasoning to access the dataset and click `Confirm`. You should receive an email once the PI approves the request; however, you can also check by seeing whether you can click the `Export` button on the project webpage.

To get the final datasets, click the `Export` button. On the left hand side, make sure under `Shared Samples` that there is a checkbox next to `All Data` by clicking it. Then, click the `Export Transactions` button when it appears. Wait for the server to process your request, and then you should have three files `ds*_tx_All_Data_*_<timestamp>.txt`.

You may need to download additional data files under "Files" in the dataset tab menu to reproduce all analyses.

Please feel free to reach out for help accessing the data, reproducing the analyses, or with any other questions you may have.
