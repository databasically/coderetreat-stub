# A sample Guardfile
# More info at https://github.com/guard/guard#readme

# guard 'rspec', :version => 2 do
#   watch(%r{^.+\.rb$})
# end

guard :shell do
  watch("gol.rb") { `clear; rspec --color --format documentation gol.rb`}
end
