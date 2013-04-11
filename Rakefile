task :build do
  `mdpress -a v4.md -s pivotal && echo "MDpress running..."`
end

task :open do
  `open v2/index.html && echo "Opened browser"`
end

task :default => [:build, :open]
