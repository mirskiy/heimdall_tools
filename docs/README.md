# HeimdallTools

HeimdallTools supplies several CLI tools to convert HDF format to be viewable in Heimdall. The converters in version 1.0.1 are:

* fortify_mapper

# Installation

Add this line to your application's Gemfile:

```
gem 'heimdall_tools', :git => "https://github.com/mitre/heimdall_tools"
```

And then execute:

    $ bundle

Clone the repo and install it yourself as:

    $ gem install heimdall_tools

```

## Command line Usage

On the Command Line, `heimdall_tools help` will print a listing of all the command with a short description.
For detailed help on any command, run `heimdall_tools help [COMMAND]`. Help can also be called with the `-h, --help` flags after any command, like `heimdall_tools fortify_mapper -h`.


## fortify_mapper

fortify_mapper translates an Fortify results FVDL file into HDF format json to be viewable in Heimdall

```
USAGE: heimdall_tools fortify_mapper [OPTIONS] -f <fortify-fvdl> -o <scan-results.json>

FLAGS:
    -j --fortify-fvdl <fortify-fvdl> : path to Fortify Scan FVDL file
    -o --output <scan-results>       : path to output scan-results json
    -V --verbose                     : verbose run [optional]

example: heimdall_tools fortify_mapper -j results.json -o output.ckl
```

## version  

Prints out the gem version

```
USAGE: heimdall_tools version
```


### NOTICE

© 2018 The MITRE Corporation.

Approved for Public Release; Distribution Unlimited. Case Number 18-3678.  

### NOTICE  

This software was produced for the U. S. Government under Contract Number HHSM-500-2012-00008I, and is subject to Federal Acquisition Regulation Clause 52.227-14, Rights in Data-General.  

No other use other than that granted to the U. S. Government, or to those acting on behalf of the U. S. Government under that Clause is authorized without the express written permission of The MITRE Corporation.

For further information, please contact The MITRE Corporation, Contracts Management Office, 7515 Colshire Drive, McLean, VA  22102-7539, (703) 983-6000.

### NOTICE

DISA STIGs are published by DISA IASE, see: https://iase.disa.mil/Pages/privacy_policy.aspx
