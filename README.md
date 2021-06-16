# math_revisited
study notes, comments and etc.

# wiki tools installation guide
## gollum
### mac os x 10.11 install gollum(As 2021.June.2):
Editing
### ubuntu 18.04 install gollum(As 2021.June.2):
#### 1. install ruby(2.5)
`sudo apt-get install ruby-full`
#### 2. install gollum dependencies
`sudo apt-get install -y ruby ruby-dev make zlib1g-dev libicu-dev build-essential git asciidoc cmake pkg-config libssl-dev`
#### 3.install gollum  
`sudo gem install gollum`
#### 4. launch gollum
cd to the wiki directory(eg. git clone ...):
`gollum --mathjax -p 4567` 
**Remark:** The tree of wiki files created in gollum is flat processed & displayed within github-wiki, it will cause duplicated name bugs unless we use some namespace-title naming standards.

# Open Problems that I am interested
## Invariant Subspace Problem
## Krzyz Conjecture

## As so far, I believe one of the most efficient ways to organize personal knowledge is as follows:
* use free version wiki tools such as confluence wiki (2GB, sufficient for string writers), free tex, markdown and other useful plugins provided.
* use github to save  files  in cloud, together with vpn(set for `raw.githubusercontent.com`), github (ex. in chrome) would explicit picture, pdf contents. 
* in addition, one can use `飞书`, `google drive` to get 200GB, 15GB cloud spaces. 
