Retjilp: Native Auto-retweet bot 
--------------------------------
<http://el-tramo.be/blog/retjilp>

Retjilp logs into your account, scans all the tweets from your following
list or another defined list for a set of matching words, and retweets 
the ones that match (using the native retweet API).
 
Prerequisites of this script are Ruby and the `oauth` and `json_pure` 
ruby gems (`gem install <gem>`).

To use this script, you will need to have registered an application with
<http://twitter.com/apps> to get a consumer key and secret, and fill these 
values in the `config` file. After having changed the `config` file, move it 
to a dir `.retjilp` in your homedir (i.e. `~/.retjilp`).

To start the script, run 

    ./retjilp.rb
    
To get a list of command-line parameters, use the `--help` option.

The first time the script is run, it will ask you to authorize the application
in your twitter account. After this is done, the script will automatically log
in the next time it is run.
