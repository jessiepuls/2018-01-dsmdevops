require 'rspec/core/rake_task'
require 'find'
rspec_options = '--format documentation'

namespace :spec do
  desc 'Aws Integrations'
  RSpec::Core::RakeTask.new(:aws_integration) do |t|
    t.pattern = Dir.glob('./test/aws_integration/*_spec.rb')
    t.rspec_opts = rspec_options
  end
end

