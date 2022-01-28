github.dismiss_out_of_range_messages

check_files = [
  'README.md',
  'path/to/hello.txt',
]

git.modified_files.map do |file|
  warn ":man_police_officer: #{file} が変更されました :man_police_officer:" if check_files.include?(file)
end

message '変更行が多いので分けてくれると嬉しい :cry: （無理に分けなくてもいいです）' if git.lines_of_code > 1000
