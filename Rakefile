# -*- coding: utf-8 -*-
$:.unshift('/Library/RubyMotion/lib')
require 'motion/project/template/ios'
require './motion/slide_over_control'

require 'bundler'
require 'motion/project/template/gem/gem_tasks'
Bundler.require

require 'ruby_motion_query'

Motion::Project::App.setup do |app|
  app.name = 'rmq-slide-over-control'
  app.identifier = 'com.infinitered.rmq-slide-over-control'

  app.sdk_version = "8.1"
  app.deployment_target = "7.1"
  app.frameworks += %w[MapKit] # Only needed in example app, not in your app (unless you're using maps of course)
end
