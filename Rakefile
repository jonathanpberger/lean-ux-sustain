task :build do
  `mdpress -a talk.md -s pivotal`
end

task :open do
  `open talk/index.html`
end

task :default => [:build, :open]
