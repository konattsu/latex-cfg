FROM texlive/texlive:latest

# Install Noto CJK fonts for LuaLaTeX
RUN apt-get update \
    && apt-get install -y fonts-noto-cjk \
    && rm -rf /var/lib/apt/lists/*
