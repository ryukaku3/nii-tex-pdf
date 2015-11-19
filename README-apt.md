### nii-tex-pdf

#### repo file.
    # vi /etc/apt/sources.list.d/nii-tex-pdf.list 

####
    ##-------------------------------------
    ## nii-tex-pdf
    ##-------------------------------------
    deb https://ryukaku3.github.io/nii-tex-pdf/ubuntu/14/packages ./

#### apt
    # apt-get update
    （リポジトリのキャッシュのみを更新する）
    # apt-cache search nii-pdf
    # apt-get install nii-pdf

#### DEPENDS perl
    libyaml-perl(deb)
    libxml-libxml-perl(deb)
    List::BinarySearch::XS(cpan)
    JSON::RPC(cpan)
