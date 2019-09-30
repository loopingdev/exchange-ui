# Exchange New UI

## Installation steps

1. `git clone https://github.com/edwinvyp/exchange-ui.git`
2. `cd exchange-ui`
3. `bundle install`
4. Search for 'edwinvyp.com' in the repository and make sure you replace all instances of it with your domain
 ## Use This Command:
 `find ./ -type f -exec sed -i -e 's/edwinvyp.com/yourdomain.com/g' {} \;`
 'find ./ -type f -exec sed -i -e 's/KoinFit/namaexchange/g' {} \;`'


5. `chmod +x bin/*`
6. `bin/setup`
7. `bin/init_config`
8. `bundle exec rake assets:precompile`
9. `bundle exec rails server -p 4000`


# To do: 
## `Tradingview integration`

