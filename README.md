# InCLow Homepage

Welcome to InCLow homepage. Below is the instructions about how to modify your own profile.

## How to edit your profile:

Go to `content`-`authors`, if your name is not there, please create a new folder and place `_index.md` and `avatar.jpg` (your photo). Your personal informations are written in the former where you can change your descriptions by yourself!

## How to update publications:

Find your awesome works not on the websit? Simply copy and paste their **bibtex** into publications.bib (**remember to add comma!**) and save it. Then it will appear on the InCLow homepage automatically! 

**It would be great if you could manually add 'year', 'url', 'month' fields (if not exists) for better visualization, like below:**

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

- Have new achievements? Annouce your news at `content`-`post`! Detailed instructions are described in the example `index.md` files.

- New position opening? Update the information in `content`-`join`-`index.md`.

## Modify websit structure

- All files about websit structure are stored under `config/_default`.


# For more questions, please also refer to [Hugo Box Official Document](https://docs.hugoblox.com/).
