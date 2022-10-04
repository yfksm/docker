FROM almalinux/almalinux

RUN yum install -y\
    vim git wget procps

RUN mkdir -p ~/.vim/pack/themes/start &&\
    cd ~/.vim/pack/themes/start &&\
    git clone https://github.com/dracula/vim.git dracula &&\
    cd ~ &&\
    git clone https://github.com/yfksm/dotfiles.git &&\
    cp ~/dotfiles/.vimrc ~ &&\
    rm -rf ~/dotfiles

