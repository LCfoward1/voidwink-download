FFmpeg 64-bit static Windows build from www.gyan.dev

Version: 9.1-full_build-www.gyan.dev

License: GPL v3

Source Code: https://github.com/FFmpeg/FFmpeg/commit/74e4393595

External Assets
frei0r plugins:   https://www.gyan.dev/ffmpeg/builds/ffmpeg-frei0r-plugins
lensfun database: https://www.gyan.dev/ffmpeg/builds/ffmpeg-lensfun-db
whisper models:   https://huggingface.co/ggerganov/whisper.cpp/tree/main

release-full build configuration: 

ARCH                      x86 (generic)
big-endian                no
runtime cpu detection     yes
standalone assembly       yes
x86 assembler             nasm
MMX enabled               yes
MMXEXT enabled            yes
SSE enabled               yes
SSSE3 enabled             yes
AESNI enabled             yes
CLMUL enabled             yes
AVX enabled               yes
AVX2 enabled              yes
AVX-512 enabled           yes
AVX-512ICL enabled        yes
XOP enabled               yes
FMA3 enabled              yes
FMA4 enabled              yes
i686 features enabled     yes
CMOV is fast              yes
EBX available             yes
6 registers available     yes
7 registers available     yes
debug symbols             yes
strip symbols             yes
optimize for size         no
optimizations             yes
static                    yes
shared                    no
network support           yes
threading support         pthreads
safe bitstream reader     yes
texi2html enabled         no
perl enabled              yes
pod2man enabled           yes
makeinfo enabled          yes
makeinfo supports HTML    yes
experimental features     yes
xmllint enabled           yes

External libraries:
avisynth                libgsm                  libsvtav1
bzlib                   libharfbuzz             libsvtjpegxs
cairo                   libilbc                 libtheora
chromaprint             libjxl                  libtwolame
frei0r                  liblc3                  libuavs3d
gmp                     liblcevc_dec            libvidstab
gnutls                  liblensfun              libvmaf
iconv                   libmodplug              libvo_amrwbenc
ladspa                  libmp3lame              libvorbis
lcms2                   libmysofa               libvpx
libaom                  liboapv                 libvvenc
libaribb24              libopencolorio          libwebp
libaribcaption          libopencore_amrnb       libx264
libass                  libopencore_amrwb       libx265
libastcenc              libopenjpeg             libxavs2
libbluray               libopenmpt              libxevd
libbs2b                 libopus                 libxeve
libcaca                 libplacebo              libxml2
libcdio                 libqrencode             libxvid
libcodec2               libquirc                libzimg
libcurl                 librabbitmq             libzmq
libdav1d                librav1e                libzvbi
libdavs2                librist                 lzma
libdvdnav               librubberband           mediafoundation
libdvdread              libshine                openal
libflite                libsnappy               sdl2
libfontconfig           libsoxr                 vapoursynth
libfreetype             libspeex                whisper
libfribidi              libsrt                  zlib
libgme                  libssh

External libraries providing hardware acceleration:
amf                     d3d12va                 nvdec
cuda                    dxva2                   nvenc
cuda_llvm               ffnvcodec               opencl
cuvid                   libmfx                  vaapi
d3d11va                 libvpl                  vulkan

Libraries:
avcodec                 avformat                swscale
avdevice                avutil
avfilter                swresample

Programs:
ffmpeg                  ffplay                  ffprobe

Enabled decoders:
aac                     flv                     pcm_u16le
aac_fixed               fmvc                    pcm_u24be
aac_latm                fourxm                  pcm_u24le
aasc                    fraps                   pcm_u32be
ac3                     frwu                    pcm_u32le
ac3_fixed               ftr                     pcm_u8
acelp_kelvin            g2m                     pcm_vidc
adpcm_4xm               g723_1                  pcx
adpcm_adx               g728                    pdv
adpcm_afc               g729                    pfm
adpcm_agm               gdv                     pgm
adpcm_aica              gem                     pgmyuv
adpcm_argo              gif                     pgssub
adpcm_circus            gremlin_dpcm            pgx
adpcm_ct                gsm                     phm
adpcm_dtk               gsm_ms                  photocd
adpcm_ea                h261                    pictor
adpcm_ea_maxis_xa       h263                    pixlet
adpcm_ea_r1             h263i                   pjs
adpcm_ea_r2             h263p                   png
adpcm_ea_r3             h264                    ppm
adpcm_ea_xas            h264_amf                prores
adpcm_g722              h264_cuvid              prores_raw
adpcm_g726              h264_qsv                prosumer
adpcm_g726le            hap                     psd
adpcm_ima_acorn         hca                     ptx
adpcm_ima_alp           hcom                    qcelp
adpcm_ima_amv           hdr                     qdm2
adpcm_ima_apc           hevc                    qdmc
adpcm_ima_apm           hevc_amf                qdraw
adpcm_ima_citrix        hevc_cuvid              qoa
adpcm_ima_cunning       hevc_qsv                qoi
adpcm_ima_dat4          hnm4_video              qpeg
adpcm_ima_dk3           hq_hqa                  qtrle
adpcm_ima_dk4           hqx                     r10k
adpcm_ima_ea_eacs       huffyuv                 r210
adpcm_ima_ea_sead       hymt                    ra_144
adpcm_ima_escape        iac                     ra_288
adpcm_ima_hvqm2         idcin                   ralf
adpcm_ima_hvqm4         idf                     rasc
adpcm_ima_iss           iff_ilbm                rawvideo
adpcm_ima_magix         ilbc                    realtext
adpcm_ima_moflex        imc                     rka
adpcm_ima_mtf           imm4                    rl2
adpcm_ima_oki           imm5                    roq
adpcm_ima_pda           imm6                    roq_dpcm
adpcm_ima_qt            indeo2                  rpza
adpcm_ima_rad           indeo3                  rscc
adpcm_ima_smjpeg        indeo4                  rtv1
adpcm_ima_ssi           indeo5                  rv10
adpcm_ima_wav           interplay_acm           rv20
adpcm_ima_ws            interplay_dpcm          rv30
adpcm_ima_xbox          interplay_video         rv40
adpcm_ms                ipu                     rv60
adpcm_mtaf              jacosub                 rw2
adpcm_n64               jpeg2000                s302m
adpcm_psx               jpegls                  sami
adpcm_psxc              jv                      sanm
adpcm_rhetorex          kgv1                    sbc
adpcm_sanyo             kmvc                    scpr
adpcm_sbpro_2           lagarith                screenpresso
adpcm_sbpro_3           lead                    sdx2_dpcm
adpcm_sbpro_4           libaom_av1              sga
adpcm_swf               libaribb24              sgi
adpcm_thp               libaribcaption          sgirle
adpcm_thp_le            libastcenc              sheervideo
adpcm_vima              libcodec2               shorten
adpcm_xa                libdav1d                simbiosis_imx
adpcm_xmd               libdavs2                sipr
adpcm_yamaha            libgsm                  siren
adpcm_zork              libgsm_ms               smackaud
agm                     libilbc                 smacker
ahx                     libjxl                  smc
aic                     libjxl_anim             smvjpeg
alac                    liblc3                  snow
alias_pix               libopencore_amrnb       sol_dpcm
als                     libopencore_amrwb       sp5x
amrnb                   libopus                 speedhq
amrwb                   libspeex                speex
amv                     libsvtjpegxs            srgc
anm                     libuavs3d               srt
ansi                    libvorbis               ssa
anull                   libvpx_vp8              stl
apac                    libvpx_vp9              subrip
ape                     libxevd                 subviewer
apng                    libzvbi_teletext        subviewer1
aptx                    loco                    sunrast
aptx_hd                 lscr                    svq1
apv                     m101                    svq3
arbc                    mace3                   tak
argo                    mace6                   targa
ass                     magicyuv                targa_y216
asv1                    mdec                    tdsc
asv2                    media100                text
atrac1                  metasound               theora
atrac3                  microdvd                thp
atrac3al                mimic                   tiertexseqvideo
atrac3p                 misc4                   tiff
atrac3pal               mjpeg                   tmv
atrac9                  mjpeg_cuvid             truehd
aura                    mjpeg_qsv               truemotion1
aura2                   mjpegb                  truemotion2
av1                     mlp                     truemotion2rt
av1_amf                 mmvideo                 truespeech
av1_cuvid               mobiclip                tscc
av1_qsv                 motionpixels            tscc2
avrn                    movtext                 tta
avrp                    mp1                     twinvq
avs                     mp1float                txd
avui                    mp2                     ulti
bethsoftvid             mp2float                utvideo
bfi                     mp3                     v210
bink                    mp3adu                  v210x
binkaudio_dct           mp3adufloat             vb
binkaudio_rdft          mp3float                vble
bintext                 mp3on4                  vbn
bitpacked               mp3on4float             vc1
bmp                     mpc7                    vc1_cuvid
bmv_audio               mpc8                    vc1_qsv
bmv_video               mpeg1_cuvid             vc1image
bonk                    mpeg1video              vcr1
brender_pix             mpeg2_cuvid             vmdaudio
c93                     mpeg2_qsv               vmdvideo
cavs                    mpeg2video              vmix
cbd2_dpcm               mpeg4                   vmnc
ccaption                mpeg4_cuvid             vnull
cdgraphics              mpegvideo               vorbis
cdtoons                 mpl2                    vp3
cdxl                    msa1                    vp4
cfhd                    mscc                    vp5
cinepak                 msmpeg4v1               vp6
clearvideo              msmpeg4v2               vp6a
cljr                    msmpeg4v3               vp6f
cllc                    msnsiren                vp7
comfortnoise            msp2                    vp8
cook                    msrle                   vp8_cuvid
cpia                    mss1                    vp8_qsv
cri                     mss2                    vp9
cscd                    msvideo1                vp9_amf
cyuv                    mszh                    vp9_cuvid
dca                     mts2                    vp9_qsv
dds                     mv30                    vplayer
derf_dpcm               mvc1                    vqa
dfa                     mvc2                    vqc
dfpwm                   mvdv                    vvc
dirac                   mvha                    vvc_qsv
dnxhd                   mwsc                    wady_dpcm
dolby_e                 mxpeg                   wavarc
dpx                     nellymoser              wavpack
dsd_lsbf                notchlc                 wbmp
dsd_lsbf_planar         nuv                     wcmv
dsd_msbf                on2avc                  webp
dsd_msbf_planar         opus                    webp_anim
dsicinaudio             osq                     webvtt
dsicinvideo             paf_audio               wmalossless
dss_sp                  paf_video               wmapro
dst                     pam                     wmav1
dvaudio                 pbm                     wmav2
dvbsub                  pcm_alaw                wmavoice
dvdsub                  pcm_bluray              wmv1
dvvideo                 pcm_dvd                 wmv2
dxa                     pcm_dvda                wmv3
dxtory                  pcm_f16le               wmv3image
dxv                     pcm_f24le               wnv1
eac3                    pcm_f32be               wrapped_avframe
eacmv                   pcm_f32le               ws_snd1
eamad                   pcm_f64be               xan_dpcm
eatgq                   pcm_f64le               xan_wc3
eatgv                   pcm_lxf                 xan_wc4
eatqi                   pcm_mulaw               xbin
eightbps                pcm_s16be               xbm
eightsvx_exp            pcm_s16be_planar        xface
eightsvx_fib            pcm_s16le               xl
escape124               pcm_s16le_planar        xma1
escape130               pcm_s24be               xma2
evrc                    pcm_s24daud             xpm
exr                     pcm_s24le               xsub
fastaudio               pcm_s24le_planar        xwd
ffv1                    pcm_s32be               y41p
ffvhuff                 pcm_s32le               ylc
ffwavesynth             pcm_s32le_planar        yop
fic                     pcm_s64be               yuv4
fits                    pcm_s64le               zero12v
flac                    pcm_s8                  zerocodec
flashsv                 pcm_s8_planar           zlib
flashsv2                pcm_sga                 zmbv
flic                    pcm_u16be

Enabled encoders:
a64multi                hevc_d3d12va            pcm_s32be
a64multi5               hevc_mf                 pcm_s32le
aac                     hevc_nvenc              pcm_s32le_planar
aac_mf                  hevc_qsv                pcm_s64be
ac3                     hevc_vaapi              pcm_s64le
ac3_fixed               hevc_vulkan             pcm_s8
ac3_mf                  huffyuv                 pcm_s8_planar
adpcm_adx               jpeg2000                pcm_u16be
adpcm_argo              jpegls                  pcm_u16le
adpcm_g722              libaom_av1              pcm_u24be
adpcm_g726              libastcenc              pcm_u24le
adpcm_g726le            libcodec2               pcm_u32be
adpcm_ima_alp           libgsm                  pcm_u32le
adpcm_ima_amv           libgsm_ms               pcm_u8
adpcm_ima_apm           libilbc                 pcm_vidc
adpcm_ima_qt            libjxl                  pcx
adpcm_ima_ssi           libjxl_anim             pdv
adpcm_ima_wav           liblc3                  pfm
adpcm_ima_ws            libmp3lame              pgm
adpcm_ms                liboapv                 pgmyuv
adpcm_swf               libopencore_amrnb       phm
adpcm_yamaha            libopenjpeg             png
alac                    libopus                 ppm
alias_pix               librav1e                prores
amv                     libshine                prores_aw
anull                   libspeex                prores_ks
apng                    libsvtav1               prores_ks_vulkan
aptx                    libsvtjpegxs            qoi
aptx_hd                 libtheora               qtrle
apv_vulkan              libtwolame              r10k
ass                     libvo_amrwbenc          r210
asv1                    libvorbis               ra_144
asv2                    libvpx_vp8              rawvideo
av1_amf                 libvpx_vp9              roq
av1_d3d12va             libvvenc                roq_dpcm
av1_mf                  libwebp                 rpza
av1_nvenc               libwebp_anim            rv10
av1_qsv                 libx264                 rv20
av1_vaapi               libx264rgb              s302m
av1_vulkan              libx265                 sbc
avrp                    libxavs2                sgi
avui                    libxeve                 smc
bitpacked               libxvid                 snow
bmp                     ljpeg                   speedhq
cfhd                    magicyuv                srt
cinepak                 mjpeg                   ssa
cljr                    mjpeg_qsv               subrip
comfortnoise            mjpeg_vaapi             sunrast
dca                     mlp                     svq1
dfpwm                   movtext                 targa
dnxhd                   mp2                     text
dpx                     mp2fixed                tiff
dsd_msbf                mp3_mf                  truehd
dvbsub                  mpeg1video              tta
dvdsub                  mpeg2_qsv               ttml
dvvideo                 mpeg2_vaapi             utvideo
dxv                     mpeg2video              v210
eac3                    mpeg4                   vbn
exr                     msmpeg4v2               vc2
ffv1                    msmpeg4v3               vnull
ffv1_vulkan             msrle                   vorbis
ffvhuff                 msvideo1                vp8_vaapi
fits                    nellymoser              vp9_qsv
flac                    opus                    vp9_vaapi
flashsv                 pam                     wavpack
flashsv2                pbm                     wbmp
flv                     pcm_alaw                webvtt
g723_1                  pcm_bluray              wmav1
gif                     pcm_dvd                 wmav2
h261                    pcm_f32be               wmv1
h263                    pcm_f32le               wmv2
h263p                   pcm_f64be               wrapped_avframe
h264_amf                pcm_f64le               xbm
h264_d3d12va            pcm_mulaw               xface
h264_mf                 pcm_s16be               xsub
h264_nvenc              pcm_s16be_planar        xwd
h264_qsv                pcm_s16le               y41p
h264_vaapi              pcm_s16le_planar        yuv4
h264_vulkan             pcm_s24be               zlib
hap                     pcm_s24daud             zmbv
hdr                     pcm_s24le
hevc_amf                pcm_s24le_planar

Enabled hwaccels:
apv_vulkan              hevc_nvdec              vc1_nvdec
av1_d3d11va             hevc_nvdec_cuarray      vc1_nvdec_cuarray
av1_d3d11va2            hevc_vaapi              vc1_vaapi
av1_d3d12va             hevc_vulkan             vp8_nvdec
av1_dxva2               mjpeg_nvdec             vp8_nvdec_cuarray
av1_nvdec               mjpeg_vaapi             vp8_vaapi
av1_nvdec_cuarray       mpeg1_nvdec             vp9_d3d11va
av1_vaapi               mpeg1_nvdec_cuarray     vp9_d3d11va2
av1_vulkan              mpeg2_d3d11va           vp9_d3d12va
dpx_vulkan              mpeg2_d3d11va2          vp9_dxva2
ffv1_vulkan             mpeg2_d3d12va           vp9_nvdec
h263_vaapi              mpeg2_dxva2             vp9_nvdec_cuarray
h264_d3d11va            mpeg2_nvdec             vp9_vaapi
h264_d3d11va2           mpeg2_nvdec_cuarray     vp9_vulkan
h264_d3d12va            mpeg2_vaapi             vvc_vaapi
h264_dxva2              mpeg4_nvdec             wmv3_d3d11va
h264_nvdec              mpeg4_nvdec_cuarray     wmv3_d3d11va2
h264_nvdec_cuarray      mpeg4_vaapi             wmv3_d3d12va
h264_vaapi              prores_raw_vulkan       wmv3_dxva2
h264_vulkan             prores_vulkan           wmv3_nvdec
hevc_d3d11va            vc1_d3d11va             wmv3_nvdec_cuarray
hevc_d3d11va2           vc1_d3d11va2            wmv3_vaapi
hevc_d3d12va            vc1_d3d12va
hevc_dxva2              vc1_dxva2

Enabled parsers:
aac                     dvdsub                  mpegaudio
aac_latm                evc                     mpegvideo
ac3                     ffv1                    opus
adx                     flac                    png
ahx                     ftr                     pnm
amr                     g723_1                  prores
apv                     g729                    prores_raw
av1                     gif                     qoi
avs2                    gsm                     rv34
avs3                    h261                    rw2
bmp                     h263                    sbc
cavsvideo               h264                    sipr
cook                    hdr                     tak
cri                     hevc                    vc1
dca                     ipu                     vorbis
dirac                   jpeg2000                vp3
dnxhd                   jpegxl                  vp8
dnxuc                   jpegxs                  vp9
dolby_e                 lcevc                   vvc
dpx                     misc4                   webp
dvaudio                 mjpeg                   xbm
dvbsub                  mlp                     xma
dvd_nav                 mpeg4video              xwd

Enabled demuxers:
aa                      idf                     pcm_f64be
aac                     iff                     pcm_f64le
aax                     ifv                     pcm_mulaw
ac3                     ilbc                    pcm_s16be
ac4                     image2                  pcm_s16le
ace                     image2_alias_pix        pcm_s24be
acm                     image2_brender_pix      pcm_s24le
act                     image2pipe              pcm_s32be
adf                     image_bmp_pipe          pcm_s32le
adp                     image_cri_pipe          pcm_s8
ads                     image_dds_pipe          pcm_u16be
adx                     image_dpx_pipe          pcm_u16le
aea                     image_exr_pipe          pcm_u24be
afc                     image_gem_pipe          pcm_u24le
aiff                    image_gif_pipe          pcm_u32be
aix                     image_hdr_pipe          pcm_u32le
alp                     image_j2k_pipe          pcm_u8
amr                     image_jpeg_pipe         pcm_vidc
amrnb                   image_jpegls_pipe       pdv
amrwb                   image_jpegxl_pipe       pjs
anm                     image_jpegxs_pipe       pmp
apac                    image_pam_pipe          pp_bnk
apc                     image_pbm_pipe          pva
ape                     image_pcx_pipe          pvf
apm                     image_pfm_pipe          qcp
apng                    image_pgm_pipe          qoa
aptx                    image_pgmyuv_pipe       r3d
aptx_hd                 image_pgx_pipe          rawvideo
apv                     image_phm_pipe          rcwt
aqtitle                 image_photocd_pipe      realtext
argo_asf                image_pictor_pipe       redspark
argo_brp                image_png_pipe          rka
argo_cvg                image_ppm_pipe          rl2
asf                     image_psd_pipe          rm
ass                     image_qdraw_pipe        roq
ast                     image_qoi_pipe          rpl
astc                    image_rw2_pipe          rsd
au                      image_sgi_pipe          rso
av1                     image_sunrast_pipe      rtp
avi                     image_svg_pipe          rtsp
avisynth                image_tiff_pipe         s337m
avr                     image_vbn_pipe          sami
avs                     image_webp_pipe         sap
avs2                    image_xbm_pipe          sbc
avs3                    image_xpm_pipe          sbg
bethsoftvid             image_xwd_pipe          scc
bfi                     imf                     scd
bfstm                   ingenient               sdns
bink                    ipmovie                 sdp
binka                   ipu                     sdr2
bintext                 ircam                   sds
bit                     iss                     sdx
bitpacked               iv8                     segafilm
bmv                     ivf                     ser
boa                     ivr                     sga
bonk                    jacosub                 shorten
brstm                   jpeg_mpf                siff
c93                     jpegxl_anim             simbiosis_imx
caf                     jv                      sln
cavsvideo               ktx                     smacker
cdg                     kux                     smjpeg
cdxl                    kvag                    smush
cine                    laf                     sol
codec2                  lc3                     sox
codec2raw               libgme                  spdif
concat                  libmodplug              srt
dash                    libopenmpt              stl
data                    live_flv                str
daud                    lmlm4                   subviewer
dcstr                   loas                    subviewer1
derf                    lrc                     sup
dfa                     luodat                  svag
dfpwm                   lvf                     svs
dhav                    lxf                     swf
dirac                   m4v                     tak
dnxhd                   matroska                tedcaptions
dsf                     mca                     thp
dsicin                  mcc                     threedostr
dss                     mgsts                   tiertexseq
dts                     microdvd                tmv
dtshd                   mjpeg                   truehd
dv                      mjpeg_2000              tta
dvbsub                  mlp                     tty
dvbtxt                  mlv                     txd
dvdvideo                mm                      ty
dxa                     mmf                     usm
ea                      mods                    v210
ea_cdata                moflex                  v210x
eac3                    mov                     vag
epaf                    mp3                     vapoursynth
evc                     mpc                     vc1
ffmetadata              mpc8                    vc1t
filmstrip               mpegps                  vividas
fits                    mpegts                  vivo
flac                    mpegtsraw               vmd
flic                    mpegvideo               vobsub
flv                     mpjpeg                  voc
fourxm                  mpl2                    vpk
frm                     mpsub                   vplayer
fsb                     msf                     vqf
fwse                    msnwc_tcp               vvc
g722                    msp                     w64
g723_1                  mtaf                    wady
g726                    mtv                     wav
g726le                  musx                    wavarc
g728                    mv                      wc3
g729                    mvi                     webm_dash_manifest
gdv                     mvr                     webp_anim
genh                    mxf                     webvtt
gif                     mxg                     wsaud
gsm                     nc                      wsd
gxf                     nistsphere              wsvqa
h261                    nsp                     wtv
h263                    nsv                     wv
h264                    nut                     wve
hca                     nuv                     xa
hcom                    obu                     xbin
hevc                    ogg                     xmd
hls                     oma                     xmv
hnm                     osq                     xvag
hxvs                    paf                     xwma
iamf                    pcm_alaw                yop
ico                     pcm_f32be               yuv4mpegpipe
idcin                   pcm_f32le

Enabled muxers:
a64                     h263                    pcm_s16be
ac3                     h264                    pcm_s16le
ac4                     hash                    pcm_s24be
adts                    hds                     pcm_s24le
adx                     hevc                    pcm_s32be
aea                     hls                     pcm_s32le
aiff                    iamf                    pcm_s8
alp                     ico                     pcm_u16be
amr                     ilbc                    pcm_u16le
amv                     image2                  pcm_u24be
apm                     image2pipe              pcm_u24le
apng                    ipod                    pcm_u32be
aptx                    ircam                   pcm_u32le
aptx_hd                 ismv                    pcm_u8
apv                     iterm2                  pcm_vidc
argo_asf                ivf                     pdv
argo_cvg                jacosub                 psp
asf                     jpeg_mpf                rawvideo
asf_stream              ktx                     rcwt
ass                     kvag                    rm
ast                     latm                    roq
astc                    lc3                     rso
au                      lrc                     rtp
avi                     m4v                     rtp_mpegts
avif                    matroska                rtsp
avm2                    matroska_audio          sap
avs2                    mcc                     sbc
avs3                    md5                     scc
bit                     microdvd                segafilm
caf                     mjpeg                   segment
cavsvideo               mkvtimestamp_v2         smjpeg
chromaprint             mlp                     smoothstreaming
codec2                  mmf                     sox
codec2raw               mov                     spdif
crc                     mp2                     spx
dash                    mp3                     srt
data                    mp4                     stream_segment
daud                    mpeg1system             streamhash
dfpwm                   mpeg1vcd                sup
dirac                   mpeg1video              swf
dnxhd                   mpeg2dvd                tee
dts                     mpeg2svcd               tg2
dv                      mpeg2video              tgp
eac3                    mpeg2vob                truehd
evc                     mpegts                  tta
f4v                     mpjpeg                  ttml
ffmetadata              mxf                     uncodedframecrc
fifo                    mxf_d10                 vc1
filmstrip               mxf_opatom              vc1t
fits                    null                    voc
flac                    nut                     vvc
flv                     obu                     w64
framecrc                oga                     wav
framehash               ogg                     webm
framemd5                ogv                     webm_chunk
g722                    oma                     webm_dash_manifest
g723_1                  opus                    webp
g726                    pcm_alaw                webvtt
g726le                  pcm_f32be               whip
gif                     pcm_f32le               wsaud
gsm                     pcm_f64be               wtv
gxf                     pcm_f64le               wv
h261                    pcm_mulaw               yuv4mpegpipe

Enabled protocols:
async                   httpproxy               rtmp
bluray                  https                   rtmpe
cache                   icecast                 rtmps
concat                  ipfs_gateway            rtmpt
concatf                 ipns_gateway            rtmpte
crypto                  libamqp                 rtmpts
data                    libcurl                 rtp
dtls                    librist                 shared
fd                      libsrt                  srtp
ffrtmpcrypt             libssh                  subfile
ffrtmphttp              libzmq                  tcp
file                    md5                     tee
ftp                     mmsh                    tls
gopher                  mmst                    udp
gophers                 pipe                    udplite
http                    prompeg                 windows_handle

Enabled filters:
a3dscope                deesser                 perlin
aap                     deflate                 perms
abench                  deflicker               perspective
abitscope               deinterlace_d3d12       phase
acompressor             deinterlace_qsv         photosensitivity
acontrast               deinterlace_vaapi       pixdesctest
acopy                   dejudder                pixelize
acrossfade              delogo                  pixscope
acrossover              denoise_vaapi           pp7
acrusher                deshake                 premultiply
acue                    deshake_opencl          premultiply_dynamic
addroi                  despill                 prewitt
adeclick                detelecine              prewitt_opencl
adeclip                 dialoguenhance          procamp_vaapi
adecorrelate            dilation                program_opencl
adelay                  dilation_opencl         pseudocolor
adenorm                 displace                psnr
aderivative             doubleweave             pullup
adrawgraph              drawbox                 qp
adrc                    drawbox_vaapi           qrencode
adynamicequalizer       drawgraph               qrencodesrc
adynamicsmooth          drawgrid                quirc
aecho                   drawtext                random
aemphasis               drawvg                  readeia608
aeval                   drmeter                 readvitc
aevalsrc                dynaudnorm              realtime
aexciter                earwax                  remap
afade                   ebur128                 remap_opencl
afdelaysrc              edgedetect              removegrain
afftdn                  elbg                    removelogo
afftfilt                entropy                 repeatfields
afir                    epx                     replaygain
afireqsrc               eq                      reverse
afirsrc                 equalizer               rgbashift
aformat                 erosion                 rgbtestsrc
afreqshift              erosion_opencl          roberts
afwtdn                  estdif                  roberts_opencl
agate                   exposure                rotate
agraphmonitor           extractplanes           rubberband
ahistogram              extrastereo             sab
aiir                    fade                    scale
aintegral               feedback                scale2ref
ainterleave             fftdnoiz                scale_cuda
alatency                fftfilt                 scale_d3d11
alimiter                field                   scale_d3d12
allpass                 fieldhint               scale_qsv
allrgb                  fieldmatch              scale_vaapi
allyuv                  fieldorder              scale_vulkan
aloop                   fillborders             scdet
alphaextract            find_rect               scdet_vulkan
alphamerge              firequalizer            scharr
amerge                  flanger                 scroll
ametadata               flip_vulkan             segment
amf_capture             flite                   select
amix                    floodfill               selectivecolor
amovie                  format                  sendcmd
amplify                 fps                     separatefields
amultiply               framepack               setdar
anequalizer             framerate               setfield
anlmdn                  framestep               setparams
anlmf                   frc_amf                 setpts
anlms                   freezedetect            setrange
anoisesrc               freezeframes            setsar
anull                   frei0r                  settb
anullsink               frei0r_src              sharpness_vaapi
anullsrc                fruc_vulkan             shear
apad                    fspp                    showcqt
aperms                  fsync                   showcwt
aphasemeter             gainmap                 showfreqs
aphaser                 gblur                   showinfo
aphaseshift             gblur_vulkan            showpalette
apsnr                   geq                     showspatial
apsyclip                gfxcapture              showspectrum
apulsator               gradfun                 showspectrumpic
arealtime               gradients               showvolume
aresample               graphmonitor            showwaves
areverse                grayworld               showwavespic
arls                    greyedge                shuffleframes
arnndn                  guided                  shufflepixels
asdr                    haas                    shuffleplanes
asegment                haldclut                sidechaincompress
aselect                 haldclutsrc             sidechaingate
asendcmd                hdcd                    sidedata
asetnsamples            headphone               sierpinski
asetpts                 hflip                   signalstats
asetrate                hflip_vulkan            signature
asettb                  highpass                silencedetect
ashowinfo               highshelf               silenceremove
asidedata               hilbert                 sinc
asisdr                  histeq                  sine
asoftclip               histogram               siti
aspectralstats          hqdn3d                  smartblur
asplit                  hqx                     smptebars
ass                     hstack                  smptehdbars
astats                  hstack_qsv              sobel
astreamselect           hstack_vaapi            sobel_opencl
asubboost               hsvhold                 sofalizer
asubcut                 hsvkey                  spectrumsynth
asupercut               hue                     speechnorm
asuperpass              huesaturation           split
asuperstop              hwdownload              spp
atadenoise              hwmap                   sr_amf
atempo                  hwupload                ssim
atilt                   hwupload_cuda           ssim360
atrim                   hysteresis              stereo3d
avectorscope            iccdetect               stereotools
avgblur                 iccgen                  stereowiden
avgblur_opencl          identity                streamselect
avgblur_vulkan          idet                    subtitles
avsynctest              il                      super2xsai
axcorrelate             inflate                 superequalizer
azmq                    interlace               surround
backgroundkey           interlace_vulkan        swaprect
bandpass                interleave              swapuv
bandreject              join                    tblend
bass                    kerndeint               telecine
bbox                    kirsch                  testsrc
bench                   ladspa                  testsrc2
bilateral               lagfun                  thistogram
bilateral_cuda          latency                 threshold
biquad                  latticepal              thumbnail
bitplanenoise           lcevc                   thumbnail_cuda
blackdetect             lenscorrection          tile
blackdetect_vulkan      lensfun                 tiltandshift
blackframe              libplacebo              tiltshelf
blend                   libvmaf                 tinterlace
blend_vulkan            life                    tlut2
blockdetect             limitdiff               tmedian
blurdetect              limiter                 tmidequalizer
bm3d                    loop                    tmix
boxblur                 loudnorm                tonemap
boxblur_opencl          lowpass                 tonemap_opencl
bs2b                    lowshelf                tonemap_vaapi
bwdif                   lumakey                 tpad
bwdif_cuda              lut                     transpose
bwdif_vulkan            lut1d                   transpose_cuda
cas                     lut2                    transpose_opencl
ccrepack                lut3d                   transpose_vaapi
cellauto                lutrgb                  transpose_vulkan
channelmap              lutyuv                  treble
channelsplit            mandelbrot              tremolo
chorus                  maskedclamp             trim
chromaber_vulkan        maskedmax               unpremultiply
chromahold              maskedmerge             unsharp
chromakey               maskedmin               unsharp_opencl
chromakey_cuda          maskedthreshold         untile
chromanr                maskfun                 uspp
chromashift             mcdeint                 v360
ciescope                mcompand                v360_vulkan
codecview               median                  vaguedenoiser
color                   mergeplanes             varblur
color_vulkan            mestimate               vectorscope
colorbalance            mestimate_d3d12         vflip
colorchannelmixer       metadata                vflip_vulkan
colorchart              midequalizer            vfrdet
colorcontrast           minterpolate            vibrance
colorcorrect            mix                     vibrato
colordetect             monochrome              vidstabdetect
colorhold               morpho                  vidstabtransform
colorize                movie                   vif
colorkey                mpdecimate              vignette
colorkey_opencl         mptestsrc               virtualbass
colorlevels             msad                    vmafmotion
colormap                multiply                volume
colormatrix             negate                  volumedetect
colorspace              nlmeans                 vpp_amf
colorspace_cuda         nlmeans_opencl          vpp_qsv
colorspectrum           nlmeans_vulkan          vqe_amf
colortemperature        nnedi                   vstack
compand                 noformat                vstack_qsv
compensationdelay       noise                   vstack_vaapi
concat                  normalize               w3fdif
convolution             null                    waveform
convolution_opencl      nullsink                weave
convolve                nullsrc                 whisper
copy                    ocio                    xbr
corr                    openclsrc               xcorrelate
cover_rect              oscilloscope            xfade
crop                    overlay                 xfade_opencl
cropdetect              overlay_cuda            xfade_vulkan
crossfeed               overlay_opencl          xmedian
crystalizer             overlay_qsv             xpsnr
cue                     overlay_vaapi           xstack
curves                  overlay_vulkan          xstack_qsv
datascope               owdenoise               xstack_vaapi
dblur                   pad                     yadif
dcshift                 pad_cuda                yadif_cuda
dctdnoiz                pad_opencl              yaepblur
ddagrab                 pad_vaapi               yuvtestsrc
deband                  pal100bars              zmq
deblock                 pal75bars               zoneplate
decimate                palettegen              zoompan
deconvolve              paletteuse              zscale
dedot                   pan

Enabled bsfs:
aac_adtstoasc           h264_mp4toannexb        pgs_frame_merge
ahx_to_mp2              h264_redundant_pps      prores_metadata
apv_metadata            hapqa_extract           remove_extradata
av1_frame_merge         hevc_metadata           setts
av1_frame_split         hevc_mp4toannexb        showinfo
av1_metadata            imx_dump_header         side_data
chomp                   jpegapp                 smpte436m_to_eia608
dca_core                lcevc_merge             text2movsub
dovi_rpu                lcevc_metadata          trace_headers
dovi_split              media100_to_mjpegb      trim
dts2pts                 mjpeg2jpeg              truehd_core
dump_extradata          mjpega_dump_header      vp9_metadata
dv_error_marker         mov2textsub             vp9_raw_reorder
eac3_core               mpeg2_metadata          vp9_superframe
eia608_to_smpte436m     mpeg4_unpack_bframes    vp9_superframe_split
evc_frame_merge         noise                   vvc_metadata
extract_extradata       null                    vvc_mp4toannexb
filter_units            opus_metadata
h264_metadata           pcm_rechunk

Enabled indevs:
dshow                   lavfi                   openal
gdigrab                 libcdio                 vfwcap

Enabled outdevs:
caca

release-full external libraries' versions: 

amf-headers         1.5.3-1
aom                 v3.15.3-196-ge0425ecc02
aribb24             v1.0.3-5-g5e9be27
astc-encoder        5.7.1-115-gdba7cfd
avisynth+           v3.7.6-82-gb5ec8855
cairo               1.18.6-9-g07adef44b
chromaprint         1.6.2-1
codec2              1.2.0-108-g310777b1
curl                curl-8_23_0-379-g9637d6b844
dav1d               1.5.4-58-g39834d7f
davs2               1.7-1-gb41cf11
dvdnav              7.0.0-18-g8147ccd
dvdread             7.1.1-125-g0f30df5
ffnvcodec           n13.1.15.0-4-gf205307
flite               v2.2-55-g6c9f20d
freetype            VER-2-15-0-30-gdbb00e52
frei0r              v1.5-497-g6156f2e
fribidi             v1.0.18
game-music-emu      0.6.3-250-g8238afd
gsm                 1.0.24-1
harfbuzz            15.1.0-143-g7621b1cf
ladspa-sdk          1.17-2
lame                4.0-1
lc3                 v1.1.3-11-gf9c127f
lcms2               2.20-1
lensfun             v0.3.2-3456-g52cf1a7b
libaribcaption      v1.0.0-121-g517b011
libass              0.17.5-25-g21b5a54
libbluray           1.5.1-6-g1398cc9
libbs2b             3.1.0
libcaca             0.99.beta20-8
libcdio-paranoia    10.2+2.0.2-2
libilbc             v3.0.4-346-g6adb26d4a4
libjxl              v0.13-snapshot-1-g0c65c190
liblcevc-dec        4.3.1
libmodplug          0.8.9.0-5
libmysofa           v1.3.1-79-g648eed0
libopencolorio      v1.0.8-961-g22dd9c4f
libplacebo          v7.387.0-66-g58dfee7
librabbitmq         v0.18.1-1-g540e497
librist             v0.2.20-18-ga911bee
libsoxr             0.1.3
libssh              0.12.2-1
libvo-amrwbenc      v0.1.3-7-g884dd24
libvpl              v2.17.0-2-g412c5cf
libwebp             v1.6.0-398-g7c382bd
openal-soft         255a0e2785
openapv             v1.1.3.0-3-g3f02913
opencl-headers      v2026.05.29-11-g82f6031
opencl-loader       v2026.05.29-9-gd0be526
opencore-amr        0.1.6-1
openjpeg2           2.5.4-2
openmpt             libopenmpt-0.2.6774-beta20-11233-g8ec17a9c
opus                v1.6.1-101-g0145a624
qrencode            v4.0.0-rc3-102-g715e29f
quirc               v1.2-14-gf2e4271
rav1e               p20250624-8-g31435de
rubberband          v4.0.0-2-ge4296ac
SDL                 release-3.4.0-1837-gfda4ece27
shine               3.1.1-59-gab5e352
snappy              1.3.1-1
speex               Speex-1.2.1-58-g09b569d
srt                 v1.5.7-25-g80e0bc4
SVT-AV1             v4.3.0-139-gd0d5c7e01
SVT-JPEG-XS         v0.10.0-31-g2dc3564
theora              v1.2.0alpha1-224-g28fd5ec
twolame             0.4.0-3
uavs3d              1.2
vaapi               2.11.0.pre1-281-gf052e984
vapoursynth         R82-2-gdfe97e09
vidstab             v1.1.0-291-ge2445c4
vmaf                v3.2.1-71-ga6ed0f1
vorbis              v1.3.7-37-g1b75110b
vpx                 v1.17.0-100-ge019cffb8
vulkan-loader       sdk-0.1.0-4138-g0b137080
vvenc               v1.14.0-471-ga455d51
whisper             v1.9.5-334-g5922450f
x264                0.165.3223
x265                4.3-107-g0aa41217
xavs2               1.4
xevd                v0.8.0
xeve                v0.7.1
xvidcore            1.3.7-5
zeromq              4.3.5-5
zimg                release-3.0.6-253-g67e0603
zvbi                v0.2.46

