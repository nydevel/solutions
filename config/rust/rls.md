# Rust language server

## RLS in nightly build

Right now rls can't be accessed in nightly build, whell... it can be, but but not in all builds.  
So, you can chack it there: https://rust-lang.github.io/rustup-components-history/  
And in last column you can see whih version support rls (and only rls).  

After this just run:  
`rustup install nightly-2020-11-25` (current version supported rls)
And then, for example:  
`rustup component add rls rust-analysis rust-src`
