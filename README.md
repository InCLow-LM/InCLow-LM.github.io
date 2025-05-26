# InCLow Homepage

Welcome to InCLow homepage. Below is the instructions about how to modify your own profile.

## How to edit your profile:

Go to `content`-`authors`, if your name is not there, please create a new folder and place `_index.md` and `avatar.jpg` (your photo). Your personal informations are written in the former where you can change your descriptions by yourself!

## How to update publications:

Find your awesome paper not on the websit? Simply paste its **bibtex** into `publications.bib` under your name (e.g., `# Jirui Qi`). Then it will appear on the InCLow homepage automatically! 

**Plus, it would be great if you could manually add 'year', 'url', 'month' fields (if not exists), like below:**

```
@inproceedings{your-awesome-paper,
    title = {...},
    author = {...},
    month = nov,
    year = {2025},
    url = {https://arxiv.org/abs/xxxx.xxxxx},
}
```

## Updates in News and Joining Information:

- Have new achievement? Annouce your news at `content`-`_index.md`-`Latest News` to let more people see it!

- New position opening? Update the information in `content`-`join`-`index.md`.

## Modify websit structure

- All configuration files about websit design and format are stored under `config/_default`.


# For more questions, please also refer to [Hugo Box Official Document](https://docs.hugoblox.com/).
