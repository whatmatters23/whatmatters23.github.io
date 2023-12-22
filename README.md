# What Truly Matters in Trajectory Prediction for Autonomous Driving?

This is the repository that contains source code for the [whatmatters website](https://whatmatters23.github.io).

If you find our work useful, please cite:
```
@article{haoran2023whatmatters
  author    = {Haoran Wu, Tran Phong, Cunjun Yu, Panpan Cai, Sifa Zheng, David Hsu},
  title     = {What Truly Matters in Trajectory Prediction for Autonomous Driving?},
  journal   = {NeurIPS},
  year      = {2023},
}
```

# How to test locally:

Follow this website [Test locally](https://kbroman.org/simple_site/pages/local_test.html)

(0. Optional to install ruby)
```bash
sudo apt-get install ruby-full
```

1. Install github-pages gem (sometimes need to add `sudo` to have persmission to install)
```bash
gem install github-pages
```

2. Install jekyll (following this page https://jekyllrb.com/docs/installation/ubuntu/)

```bash
echo '# Install Ruby Gems to ~/gems' >> ~/.bashrc
echo 'export GEM_HOME="$HOME/gems"' >> ~/.bashrc
echo 'export PATH="$HOME/gems/bin:$PATH"' >> ~/.bashrc
source ~/.bashrc

gem install jekyll bundler
```

2. Build jekyl
```bash
jekyll build
```

3. Serve
```bash
jekyll serve
```

# Website License
<a rel="license" href="http://creativecommons.org/licenses/by-sa/4.0/"><img alt="Creative Commons License" style="border-width:0" src="https://i.creativecommons.org/l/by-sa/4.0/88x31.png" /></a><br />This work is licensed under a <a rel="license" href="http://creativecommons.org/licenses/by-sa/4.0/">Creative Commons Attribution-ShareAlike 4.0 International License</a>.
