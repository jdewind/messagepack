desc "Compile main"
task :compile => :clean do
  sh "gcc -Os *.c -o main"
end

desc "Compile and run main"
task :run => :compile do
  sh "./main"
end

desc "Clean"
task :clean do
  rm_f "main"
end

task :default => :run
