# -*- coding: utf-8 -*-
$:.unshift("/Library/RubyMotion/lib")
require 'motion/project/template/ios'
require "bundler/gem_tasks"
require "bundler/setup"

Motion::Project::App.setup do |app|
  app.name = 'rmq'
  app.identifier = 'com.infinitered.rmq'
  app.device_family = [:iphone, :ipad]
  app.prerendered_icon = true
  app.interface_orientations = [:portrait, :landscape_left, :landscape_right, :portrait_upside_down]
end

require 'ruby_motion_query'