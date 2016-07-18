source 'https://supermarket.chef.io'

metadata

cookbook "iis", github: "taylormonacelli/iis", branch: "tm/test-workaround-ws7e"

group :integration do
  cookbook 'yum'
  cookbook 'apt'
  cookbook 'php_test', path: './test/cookbooks/php_test'
end
