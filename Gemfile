#  Copyright 2016 VoxPupuli
#
#  Licensed under the Apache License, Version 2.0 (the "License");
#  you may not use this file except in compliance with the License.
#  You may obtain a copy of the License at
#
#      http://www.apache.org/licenses/LICENSE-2.0
#
#  Unless required by applicable law or agreed to in writing, software
#  distributed under the License is distributed on an "AS IS" BASIS,
#  WITHOUT WARRANTIES OR CONDITIONS OF ANY KIND, either express or implied.
#  See the License for the specific language governing permissions and
#  limitations under the License.

source "https://rubygems.org"

group :test do
  gem 'rake'
  gem 'rubocop', '0.37.0'
  gem 'rspec'
  gem 'voxpupuli-release', git: 'git://github.com/voxpupuli/voxpupuli-release-gem.git'
  gem 'puppetlabs_spec_helper'
end

group :development do
  gem 'travis'
  gem 'travis-lint'
  gem 'guard-rake'
end
