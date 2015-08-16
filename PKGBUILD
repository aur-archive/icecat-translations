# Maintainer: Zatherz <zatherz at linux dot pl>
# Based on outdated icecat-i18n package

pkgname=icecat-translations
pkgver=31.2.0
pkgrel=6
pkgdesc="Up-to-date language packs for IceCat"
arch=('any')
license=('MPL')
url="http://www.gnu.org/software/gnuzilla/"
depends=("icecat>=${pkgver}")

source=("ftp://ftp.gnu.org/gnu/gnuzilla/${pkgver}/langpacks/icecat-${pkgver}."{ach,af,an,ar,as,ast,be,bg,bn-BD,bn-IN,br,bs,ca,cs,csb,cy,da,de,el,en-GB,en-US,en-ZA,eo,es-AR,es-CL,es-ES,es-MX,et,eu,fa,ff,fi,fr,fy-NL,ga-IE,gd,gl,gu-IN,he,hi-IN,hr,hsb,hu,hy-AM,id,is,it,ja,ja-JP-mac,kk,km,kn,ko,ku,lij,lt,lv,mai,mk,ml,mr,ms,nb-NO,nl,nn-NO,or,pa-IN,pl,pt-BR,pt-PT,rm,ro,ru,si,sk,sl,son,sq,sr,sv-SE,ta,te,th,tr,uk,vi,xh,zh-CN,zh-TW,zu}".langpack.xpi")

# Don't extract anything
noextract=(${source[@]##*/})

package() {
  cd "$srcdir"
  for FILE in *.xpi; do
    PARSEDFILE="$(sed 's/icecat-31\.2\.0\.//g;s/\.langpack\.xpi//g' <<< "$FILE")"
    install -D -m 644 "$FILE" "${pkgdir}/usr/lib/icecat/browser/extensions/langpack-${PARSEDFILE}@icecat.mozilla.org.xpi"
  done
}

md5sums=(9b7ffb857bf9738d3d1af76f9243eed6
0412124d721da0a7bd5d218aab56e234
b67d289370cc1a6e7742c0d2de40c34a
d7e031a5b14d0b9c4fc6642c3b5b2d46
ab9062b0273696bee05d8c2996e9be46
559db22956811b86e591f8731d85156e
01b368229772df9580d014d4607e1b27
eff1239da7c8cfd168fa95ac2d30d7a4
4e2cb7f2d12e6e2d5cd2976c52839d7f
c2cd2f27880b6d6c6cdc78b272d0bf66
15a885bd4b7fa9110de35c2f22cb73a2
382e77516c89513798194561ecfc2fc0
7f89339f146fd21851bf4466c585eea1
76156a321e635430ff62363eb3d33634
90a60bf42d69c0867fa22292f4e09cb3
89355f6bf0c552cd20a4c221bc2a197c
01bec39705d8689899b2977bce1a5405
ac4f8639442eab17df47dd0a049a1bd8
59c11c30caea17ebfe01c6ec188594c5
9acaa18fca6fb00e7551211d2c3bac6f
d3cb33458626b78478aa67717e2e16e9
de887510c6b8aa00184372b328778a6f
9f2f76745221a5bf166d450d9ef0f6c0
4b56d5d3ca2f6eaf81e57b02a0d8e080
6200a09914798f4d696c6ec2d2d21b47
444e652138d9da5eceaf0703e1d86115
80feaabc2ab720dc8b0d4fda50ccbadf
4cae20fad3953452489be6aca017d03c
11c8781570159cc5bd26d8e9ff883506
0136caa0545428ccd88763b774ed831d
7ffbd78753cf237065e1eb91bbbebc57
be0841d30d9638a337438c06beb2e28e
cb4c8639600e05eb4410d551018b4f1f
258647397ea6b7dc22acbb1a3910fddd
41efcaa0fc1fd96d7b54edb4a4dcac7f
bc2118051526a5214baa00e12364def1
7a8bb4604c262747a2c891bf9aab1f39
6daee1ba8cb0bf2889a482bdaa89bedc
10a888f4eb3924c8bb88c8ff997c16cc
c71bffbcb79221898e32bdf7d4543074
4b2508d20ccf2e02d06d9c75cb35e919
f23ee10ed76e2263a65149e44b284a6c
caa22d3715ecd26d8e100708e6d3d30a
bc823b9ff183994e11cf5b2b7516942c
dc3bc5f5d083667ab244da9761c24137
ea7a7e0a66db0cfe4e5bb5c1d3fafb0e
fdf0465557bec5cb1e9e86b975905633
a464dde345a6aa5cd0d1566fe0046ae1  # ja
07ac8893f882bafb36762463287b8b9a  # ja-JP-mac 
70d775f6488602de38f47afbb2f7d1c4
02c0578baab3c167637caa89f1315707
d98859c143a8fc8bc43a6bf4e514e608
8d7a4a12c917b8c459a66870979be1ab
8f02c7fe8073f71ac348ebfc95912d7a
52ddb091718e9c4301f05bf08216551f
8d46e650de1ad54ac8b002390f787168
977bd944a8021888b6bd1bb595e078fc
8dab9f3de094621d5ae1d2a727c551a1
33141b04cfce2849135bf97a3a13dd0f
ae028f7b6ada6e2594e21c785b3acc1d
55e09a13e1dd735fcdbe0105b061b5ac
e1a0e6dd07a1331d9a2b1e8db7be503f
af842c91637e6ec4f6e293d9e33831ae
eddd627fe4d865548736d38de01c8aef
84def04eb50c23a325be13812abb6ddc
47a21f1d77dd3ab373f784369dd79db2
9b54522f1b2267837e22b153ce79dfb8
dfe865a386d3e8b081675bdf0928edd8
66e9dbc1c0b35a59d629cea39ecf8d5f
ef66906aa2bc7c342de6ff72758a3ff6
715dd92dc829d1f6576bc11304948a56
85561202c2afd90a7a8aec8de87a51bf
efd29620cee78f6a6b9f90ccffbd829f
2470028d01e4e04974a62deb41606b5d
bb2a5b020f6f93a3e62e9c6d836d1925
9d9ef03b43e149afa8e80bafe34dc8aa
77bfc2355a902bd832b9b334a4cdb4dc
7f7418b6b3a9ac199b79e1e603c9f0b3
8191aa581e7db17cc3d45d17a230272a
5941d897564e3c7309db2fad5253a040
71a1c6da33c57b977ec9fc23f3de921b
19fdcac54e4a90e0f34e50500cc41db4
ed0e67ad4809200411290cb209f3e424
83f5ee49b59d18d332b78dd4632d75b4
17d648508180224a49b6507d3b20bd90
8166f116206274ede02a646274fa50f9
c9d90b4eb4ba0f4bd234fe9b4b0f1872
7962c3096e21a558e05698b6fa11fa43
0a558256fc0351ae0270dcd130909ed0
c7d538aa026da7ba78aab03ffe819440)
