require 'rake'

begin
  require 'jeweler'
  Jeweler::Tasks.new do |gem|
    gem.name = "gen-password"
    gem.summary = %Q{A password handling library for Ruby}
    gem.description = %Q{Ruby/GenPassword is a suite of password handling methods for Ruby. It supports
the manual entry of passwords from the keyboard in both buffered and
unbuffered modes, random password generation,
phonemic password generation (for easy memorisation by human-beings) and the
encryption of passwords. It is a fork of Ruby/Password without password checking using cracklib}
    gem.email = "itsakshaymankar@gmail.com"
    gem.homepage = "http://www.docunext.com/"
    gem.authors = ["Albert Lash", "Ian Macdonald", "Akshay Mankar", "Vini Gupta"]
    gem.add_dependency "ruby-termios"
    gem.add_development_dependency "shoulda"
  end
  Jeweler::GemcutterTasks.new
rescue LoadError
  puts "Jeweler (or a dependency) not available. Install it with: sudo gem install jeweler"
end

