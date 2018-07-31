In my situation, when using the original (provided) dataset, it was giving error.
Something related to not able to decode ASCII Charaters. So I had to remove those special characters from the Dataset.

Example of Unsupported Characters which caused problem: © (0xc2), 0xc3, other characters.
Evidence: ![Image from Gyazo](https://t.gyazo.com/teams/kemuri/5b7a8890d412e704f6e547f8dcd1c5d4.png)

My used dataset is saved with the name `moes_tavern_lines_clean.txt` in the same directory as the other dataset.
