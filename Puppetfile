forge 'https://forge.puppet.com'

def default_branch(default)
  begin
    match = /(.+)_(cdpe|cdpe_ia)_\d+$/.match(@librarian.environment.name)
    match ? match[1]:default
  rescue
    default
  end
end

# Modules from the Puppet Forge
# Versions should be updated to be the latest at the time you start
mod 'puppetlabs-cd4pe', '1.4.1'
# Requirements for cd4pe
mod 'puppetlabs-concat', '6.1.0'
mod 'puppetlabs-hocon', '1.1.0'
mod 'puppetlabs-puppet_authorization', '0.5.0'
mod 'puppetlabs-stdlib', '6.2.0'
mod 'puppetlabs-docker', '3.9.1'
mod 'puppetlabs-apt', '7.3.0'
mod 'puppetlabs-translate', '2.1.0'
mod 'puppetlabs-pwshlib', '0.4.1'
mod 'puppetlabs-powershell', '3.0.1'
mod 'puppetlabs-reboot', '3.0.0'
mod 'puppetlabs-pipelines', '1.0.1'
mod 'puppetlabs-cd4pe_jobs', '1.0.0'
mod 'puppet-gitlab', '4.0.1'

# Modules from Git
# Examples: https://github.com/puppetlabs/r10k/blob/master/doc/puppetfile.mkd#examples
#mod 'apache',
#  git:    'https://github.com/puppetlabs/puppetlabs-apache',
#  commit: '1b6f89afdde0df7f9433a163d5c4b5328eac5779'

#mod 'apache',
#  git:    'https://github.com/puppetlabs/puppetlabs-apache',
#  branch: 'docs_experiment'
