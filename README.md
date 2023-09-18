# blog

## How to use git to clone project from Github (Mac)

Please refer the [Github Doc](https://docs.github.com/en/authentication/connecting-to-github-with-ssh/generating-a-new-ssh-key-and-adding-it-to-the-ssh-agent)

- Step 1: Open terminal, under the folder path `~/`

  If not sure whether at correct location, please type

  ```bash
  cd ~/
  ```

- Step 2: Generate public and private key in your device

  Copy the following code to your terminal, remeber to update email as your own registration at Github

  ```bash
  ssh-keygen -t ed25519 -C "youremail@example.com"
  ```

  Reference for the [detail](https://docs.github.com/en/authentication/connecting-to-github-with-ssh/generating-a-new-ssh-key-and-adding-it-to-the-ssh-agent)

- Step 3: Copy the public key

  Copy the following code to your terminal.

  ```bash
  $ pbcopy < ~/.ssh/id_ed25519.pub
  ```

  Reference for the [detail](https://docs.github.com/en/authentication/connecting-to-github-with-ssh/adding-a-new-ssh-key-to-your-github-account)

- Step 4: Past to your Github setting page to add key