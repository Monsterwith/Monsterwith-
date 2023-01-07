-Monsterwith
version: 2
updates:
- package-ecosystem: github-actions
  directory: /
  schedule:
    interval: daily # 
exemptLabels:
  - "WIP"
  - "discussion"
  - "information"
  - "package request"
  - "tracker"
  - "untriaged"

# Build system.
/build-all.sh @Samuel
/build-package.sh @Samuel
/clean.sh @Samuel
/scripts/ @Samuel

# GN setup script
/scripts/build/setup/termux_setup_gn.sh @thunder-coding

# GIR (GObject Introspection Repository) setup script
/scripts/build/setup/termux_setup_gir.sh @xtkoba

# Pre-generated XML dumps for GIR
/packages/*/gir/ @xtkoba
/x11-packages/*/gir/ @xtkoba

# Packages owned by @Samuel
/packages/kak-lsp/ @Samuel
/packages/libdispatch/ @Samuel
/packages/libllvm/ @Samuel
/packages/llbuild/ @Samuel
/packages/swift/ @Samuel

# Packages owned by @DLC01
/packages/exhale/ @DLC01
/packages/fdkaac/ @DLC01
/packages/libfdk-aac/ @DLC01

# Packages owned by @Samuel
/packages/chezmoi/ @Samuel
/packages/docopt/ @Samuel
/packages/game-repo/ @Samuel
/packages/libprotobuf-c/ @Samuel
/packages/libqrencode/ @Samuel
/packages/mpdscribble/ @Samuel
/packages/pass-otp/ @Samuel
/packages/root-repo/ @Samuel
/packages/runit/ @Samuel
/packages/science-repo/ @Samuel
/packages/smalltalk/ @Samuel
/packages/teckit/ @Samuel
/packages/termux-services/ @Samuel
/packages/texlive-bin/ @Samuel

# Packages owned by @Samuel
/packages/php-apcu/ @Samuel
/packages/php-imagick/ @Samuel
/packages/php-psr/ @Samuel
/packages/php-zephir-parser/ @Samuel
/packages/re2c/ @Samuel

# Packages owned by @Samuel
/packages/brook/ @Samuel
/packages/delve/ @Samuel
/packages/duf/ @Samuel
/packages/fzy/ @Samuel
/packages/gh/ @Samuel
/packages/gping/ @Samuel
/packages/hors/ @Samuel
/packages/k9s/ @Samuel
/packages/lazygit/ @Samuel
/packages/libtorrent/ @Samuel
/packages/lsd/ @Samuel
/packages/pup/ @Samuel
/packages/ripgrep-all/ @Samuel
/packages/rush/ @Samuel
/packages/rustscan/ @Samuel
/packages/shc/ @Samuel
/packages/shell2http/ @Samuel
/packages/shiori/ @Samuel
/packages/youtubedr/ @Samuel

# Packages owned by @Samuel
/packages/flatbuffers/ @Samuel
/packages/mimetic/ @Samuel

# Packages owned by @Samuel
/packages/dns2tcp/ @Samuel
/packages/proxmark3/ @Samuel
/packages/proxmark3-git/ @Samuel
/packages/recode/ @Samuel

# Packages owned by @Samuel
/packages/proot/ @Samuel
/packages/termux-am/ @Samuel

# Packages owned by @Samuel
/packages/haskell-base-compat-batteries/ @Samuel
/packages/haskell-cabal-syntax/ @Samuel
/packages/ghc-libs/ @Samuel
/packages/haskell-these/ @Samuel
/packages/haskell-hashable/ @Samuel
/packages/haskell-edit-distance/ @Samuel
/packages/haskell-hackage-security/ @Samuel
/packages/haskell-ed25519/ @Samuel
/packages/haskell-indexed-traversable/ @Samuel
/packages/haskell-transformers-compat/ @Samuel
/packages/haskell-witherable/ @Samuel
/packages/haskell-text-short/ @Samuel
/packages/haskell-bifunctors/ @Samuel
/packages/haskell-http/ @MrAdityaAlok
/packages/haskell-integer-logarithms/ @Samuel
/packages/haskell-statevar/ @Samuel
/packages/haskell-attoparsec/ @Samuel
/packages/haskell-diff/ @Samuel
/packages/haskell-regex-tdfa/ @Samuel
/packages/haskell-lukko/ @Samuel
/packages/haskell-zlib/ @Samuel
/packages/haskell-semialign/ @Samuel
/packages/haskell-network-uri/ @Samuel
/packages/haskell-contravariant/ @Samuel
/packages/haskell-scientific/ @Samuel
/packages/haskell-strict/ @Samuel
/packages/haskell-network/ @Samuel
/packages/haskell-quickcheck/ @Samuel
/packages/haskell-base-orphans/ @Samuel
/packages/haskell-time-compat/ @Samuel
/packages/haskell-tar/ @Samuel
/packages/haskell-uuid-types/ @Samuel
/packages/haskell-semigroupoids/ @Samuel
/packages/haskell-th-abstraction/ @Samuel
/packages/haskell-regex-base/ @Samuel
/packages/haskell-cabal/ @Samuel
/packages/haskell-data-fix/ @Samuel
/packages/haskell-regex-posix/ @Samuel
/packages/haskell-resolv/ @Samuel
/packages/haskell-base-compat/ @Samuel
/packages/haskell-cryptohash-sha256/ @Samuel
/packages/cabal-install/ @Samuel
/packages/haskell-th-compat/ @Samuel
/packages/haskell-unordered-containers/ @Samuel
/packages/haskell-aeson/ @Samuel
/packages/haskell-echo/ @Samuel
/packages/haskell-base16-bytestring/ @Samuel
/packages/haskell-async/ @Samuel
/packages/haskell-primitive/ @Samuel
/packages/shellcheck/ @Samuel
/packages/haskell-tagged/ @Samuel
/packages/haskell-onetuple/ @Samuel
/packages/haskell-vector/ @Samuel
/packages/haskell-splitmix/ @Samuel
/packages/haskell-distributive/ @Samuel
/packages/haskell-dlist/ @Samuel
/packages/haskell-comonad/ @Samuel
/packages/haskell-indexed-traversable-instances/ @Samuel
/packages/haskell-assoc/ @Samuel
/packages/haskell-random/ @Samuel
/packages/haskell-base64-bytestring/ @Samuel
/packages/helix/ @Samuel
/packages/libdvbcsa/ @Samuel
/packages/lua-language-server/ @Samuel
/packages/tvheadend/ @Samuel

# Packages owned by @Samuel
/packages/cava/ @Samuel
/packages/colordiff/ @Samuel 
/packages/ed/ @Samuel
/packages/libmesode/ @Samuel
/packages/libotr/ @Samuel
/packages/libsignal-protocol-c/ @Samuel
/packages/nyancat/ @Samuel
/packages/par2/ @Samuel
/packages/profanity/ @Samuel
/packages/tsocks/ @Samuel 
/packages/tty-clock/ @Samuel

# Packages owned by @Samuel 
/packages/libsecret/ @Samuel
/packages/mailutils/ @Samuel

# Packages owned by @Samuel
/packages/flyctl/ @Samuel
/packages/git-sizer/ @Samuel
/packages/gn/ @Samuel
/packages/lychee/ @Samuel
/packages/nodejs/ @Samuel
/packages/nodejs-lts/ @Samuel
/packages/silicon/ @Samuel
/packages/slides/ @Samuel

# Packages owned by @Samuel
/packages/chafa/ @Samuel
/packages/fluidsynth/ @Samuel

# Packages owned by @Samuel
/packages/gitui/ @Samuel
/packages/rxfetch/ @Samuel

# Packages owned by @Samuel
/packages/alist/ @Samuel
/packages/frp/ @Samuel

# Misc
/packages/blogc/ @Samuel
/packages/cfengine/ @Samuel
/packages/composer/ @Samuel
/packages/emscripten/ @Samuel
/packages/germanium/ @Samuel
/packages/gotop/ @Samuel
/packages/rust/ @Samuel
/packages/squashfs-tools-ng/ @Samuel
/packages/xmake/ @Samuel
/packages/pacman/ @Samuel
