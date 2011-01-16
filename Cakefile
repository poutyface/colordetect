{exec} = require('child_process')

task 'build', 'Build project from coffee to js', ->
  exec 'coffee -b -c colors.coffee', (err, stdout, stderr) ->
    throw err if err

