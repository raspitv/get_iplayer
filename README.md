# get_iplayer
get_iplayer install code

This is the code you need to copy to your command line to install get_iplayer on your Pi...

sudo bash -c "cat > /etc/apt/sources.list.d/packages.hedgerows.org.uk.list <<EOF
deb http://packages.hedgerows.org.uk/raspbian wheezy/
deb-src http://packages.hedgerows.org.uk/raspbian wheezy/
EOF
"


It starts with sudo and ends with "
