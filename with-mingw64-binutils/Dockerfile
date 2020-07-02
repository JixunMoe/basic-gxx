FROM purplekarrot/mingw-w64-x86-64:latest

RUN true \
    && apt-get -qq update \
    && apt-get -qq install -y --no-install-recommends \
        binutils \
        binutils-mingw-w64-x86-64 \
	cppcheck \
    && rm -rf /var/lib/apt/lists/*
