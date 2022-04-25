## Welcome to GitHub Pages

You can use the [editor on GitHub](https://github.com/kakashi1120/coursera-test/edit/master/README.md) to maintain and preview the content for your website in Markdown files.

Whenever you commit to this repository, GitHub Pages will run [Jekyll](https://jekyllrb.com/) to rebuild the pages in your site, from the content in your Markdown files.

### Markdown

Markdown is a lightweight and easy-to-use syntax for styling your writing. It includes conventions for

```markdown
Syntax highlighted code block

# Header 1
## Header 2
### Header 3

- Bulleted
- List

1. Numbered
2. List

**Bold** and _Italic_ and `Code` text

[Link](url) and ![Image](src)
```

For more details see [GitHub Flavored Markdown](https://guides.github.com/features/mastering-markdown/).

### Jekyll Themes

Your Pages site will use the layout and styles from the Jekyll theme you have selected in your [repository settings](https://github.com/kakashi1120/coursera-test/settings). The name of this theme is saved in the Jekyll `_config.yml` configuration file.

### Support or Contact

Having trouble with Pages? Check out our [documentation](https://docs.github.com/categories/github-pages-basics/) or [contact support](https://github.com/contact) and we’ll help you sort it out.

2. Install Git
If installed,
sudo apt-get remove --auto-remove git
For installation 

sudo apt-get install git


P: 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 - my code 

mkdir devops
Cd devops
Git init
git config --global user.email "sidd010102@gmail.com"
git config --global user.name "kakashi1120"
nano print.py , enter command , c+x , yes
Git add .
Git status
Git commit -m “message”
git remote set-url origin http
 Git remote add origin http
Git branch -M main
Git push -u origin main










4. Git_pull

git init
Git remote add origin 
Git pull origin <branch>





9. Git_config

Mkdir git_config
Cd
Git init
Git config user.email “<email>”
Git config user.name “<name>”
Cd ./.git or cd .git
Cat config
Cd ..
Ls
Ls -al

10.git log
  Mkdir git_log
Cd git_log
Git Init


Docker


Docker install
Sudo apt-get install docker.io
Sudo bash
Pull 
Docker images
Docker pull ubuntudoc
Docker images
(optional)
Docker run -itd ubuntu
Docker ps
Docker exec -it <container-id> bash
Ls
Echo abcd
Echo abcd>newfile
Exit
Docker commit <container id> k4

Push
Docker images
Docker run -itd ubuntu
Docker ps
Docker exec -it <container-id> bash
(inside ubuntu)
Echo abcd>newfile
Cat newfile
Exit
(outside)
Docker ps
Docker commit <conatiner-id> new
docker tag SOURCE_IMAGE[:TAG] dockerusername/TARGET_IMAGE[:TAG]
Docker tag new:latest <username>/dickshant:pussy
Docker login
Docker images
Docker push kakashi010102/<reponame>:<tag>






Ansible 
$ sudo apt update 
$ sudo apt install software-properties-common
 $ sudo add-apt-repository --yes --update ppa:ansible/ansible
 $ sudo apt install ansible
 Python file docker

.mkdir devops 
cd devops 

Nano app.py 
Print(“Welcome Docker file”)

nano dockerfile
FROM python
COPY . /src
CMD ["python", "/src/app.py"]

docker build . -t python_app
docker run python_app
