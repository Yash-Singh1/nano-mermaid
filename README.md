# `nano-mermaid`

Syntax highlighting for the [`mermaid` language](https://github.com/mermaid-js/mermaid) in the `nano` code editor.

## Installation

Run:

```sh
git clone https://github.com/Yash-Singh1/nano-mermaid.git
cd nano-mermaid/
```

Then run:

### Ubuntu/Debian

```sh
sudo cp mermaid.nanorc /usr/share/nano/
```

### Mac

```sh
sudo -i
mkdir /usr/local/share/nano/
echo 'include "/usr/share/nano/*.nanorc"' >> /etc/nanorc
cp mermaid.nanorc /usr/local/share/nano/
```

### Windows

<!-- markdownlint-disable-next-line MD036 -->
**Note: Remember to run as administrator**

```sh
cp mermaid.nanorc /usr/share/nano/
```

## Usage

Creating and editing a `.mermaid` file should syntax highlight.
