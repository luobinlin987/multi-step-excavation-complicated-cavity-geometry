lin@asdf:~/path-to-shell-file/computation$ lscpu
Architecture:             x86_64
  CPU op-mode(s):         32-bit, 64-bit
  Address sizes:          36 bits physical, 48 bits virtual
  Byte Order:             Little Endian
CPU(s):                   2
  On-line CPU(s) list:    0,1
Vendor ID:                GenuineIntel
  Model name:             Intel(R) Core(TM)2 Duo CPU     L7300  @ 1.40GHz
    CPU family:           6
    Model:                15
    Thread(s) per core:   1
    Core(s) per socket:   2
    Socket(s):            1
    Stepping:             10
    Frequency boost:      enabled
    CPU(s) scaling MHz:   57%
    CPU max MHz:          1401.0000
    CPU min MHz:          800.0000
    BogoMIPS:             2793.03
    Flags:                fpu vme de pse tsc msr pae mce cx8 apic sep mtrr pge mca cmov pat pse36 clflush dts acpi mmx fxs
                          r sse sse2 ht tm pbe syscall nx lm constant_tsc arch_perfmon pebs bts rep_good nopl cpuid aperfm
                          perf pni dtes64 monitor ds_cpl est tm2 ssse3 cx16 xtpr pdcm lahf_lm pti dtherm ida
Caches (sum of all):      
  L1d:                    64 KiB (2 instances)
  L1i:                    64 KiB (2 instances)
  L2:                     4 MiB (1 instance)
NUMA:                     
  NUMA node(s):           1
  NUMA node0 CPU(s):      0,1
Vulnerabilities:          
  Gather data sampling:   Not affected
  Itlb multihit:          KVM: Mitigation: VMX unsupported
  L1tf:                   Mitigation; PTE Inversion
  Mds:                    Vulnerable: Clear CPU buffers attempted, no microcode; SMT disabled
  Meltdown:               Mitigation; PTI
  Mmio stale data:        Unknown: No mitigations
  Reg file data sampling: Not affected
  Retbleed:               Not affected
  Spec rstack overflow:   Not affected
  Spec store bypass:      Vulnerable
  Spectre v1:             Mitigation; usercopy/swapgs barriers and __user pointer sanitization
  Spectre v2:             Mitigation; Retpolines; STIBP disabled; RSB filling; PBRSB-eIBRS Not affected; BHI Not affected
  Srbds:                  Not affected
  Tsx async abort:        Not affected
lin@asdf:~/path-to-shell-file/computation$ sh computation.sh 
start_time: 2025-05-31 06:24:24
******fortran program starts******
 *********************************************************
 Let us begin !
 *********************************************************
 Boundaries of sequential excavation are set, proceed
 *********************************************************
 Bidirectional conformal mapping of 1-th step excavation
 N_{1} =          500
 M_{1} =          150
 zc1=        (-4.91753137520952093E-007,-18.750000000000011)
 Outer radius of forward mapping annulus for 1th-step excavation =    1.0000000000000002     
 Inner radius of forward mapping annulus for 1th-step excavation =   0.19143032468271481     
 arg(t_{1,1})/pi*180 =  -107.89104610091496     
 arg(t_{2,1})/pi*180 =   107.89104383446261     
 *********************************************************
 Bidirectional conformal mapping of 2-th step excavation
 N_{2} =          680
 M_{2} =          150
 zc2=              (-8.4852820570342704,-21.514719055676075)
 Outer radius of forward mapping annulus for 2th-step excavation =   0.99999999999999956     
 Inner radius of forward mapping annulus for 2th-step excavation =   0.21857573045672088     
 arg(t_{1,2})/pi*180 =  -119.64452437889989     
 arg(t_{2,2})/pi*180 =   104.99383259733612     
 *********************************************************
 Bidirectional conformal mapping of 3-th step excavation
 N_{3} =          860
 M_{3} =          120
 zc3=        (-4.91753137520952093E-007,-18.750000000000011)
 Outer radius of forward mapping annulus for 3th-step excavation =    1.0000000000000004     
 Inner radius of forward mapping annulus for 3th-step excavation =   0.24148836886364622     
 arg(t_{1,3})/pi*180 =  -115.61411055595333     
 arg(t_{2,3})/pi*180 =   115.61411055540908     
 *********************************************************
 Bidirectional conformal mapping of 4-th step excavation
 N_{4} =          876
 M_{4} =          120
 zc4=               (0.0000000000000000,-26.250000000000000)
 Outer radius of forward mapping annulus for 4th-step excavation =    1.0000000000000002     
 Inner radius of forward mapping annulus for 4th-step excavation =   0.24805425293794223     
 arg(t_{1,4})/pi*180 =  -116.75394626765754     
 arg(t_{2,4})/pi*180 =   116.75394627134328     
 *********************************************************
 Bidirectional conformal mapping of 5-th step excavation
 N_{5} =          816
 M_{5} =          150
 zc5=               (0.0000000000000000,-26.250000000000000)
 Outer radius of forward mapping annulus for 5th-step excavation =    1.0000000000000004     
 Inner radius of forward mapping annulus for 5th-step excavation =   0.25551814064804546     
 arg(t_{1,5})/pi*180 =  -119.77031723721061     
 arg(t_{2,5})/pi*180 =   116.18536385679887     
 *********************************************************
 Bidirectional conformal mapping of 6-th step excavation
 N_{6} =          756
 M_{6} =          150
 zc6=               (0.0000000000000000,-26.250000000000000)
 Outer radius of forward mapping annulus for 6th-step excavation =    1.0000000000000002     
 Inner radius of forward mapping annulus for 6th-step excavation =   0.26225689833212767     
 arg(t_{1,6})/pi*180 =  -119.05137581666369     
 arg(t_{2,6})/pi*180 =   119.05137581755670     
 *********************************************************
 Bidirectional conformal mapping of 7-th step excavation
 N_{7} =          988
 M_{7} =          150
 zc7=               (0.0000000000000000,-30.000000000000000)
 Outer radius of forward mapping annulus for 7th-step excavation =    1.0000000000000002     
 Inner radius of forward mapping annulus for 7th-step excavation =   0.26661024497968133     
 arg(t_{1,7})/pi*180 =  -119.76795995340333     
 arg(t_{2,7})/pi*180 =   119.76795998776129     
 *********************************************************
 Bidirectional conformal mapping of 8-th step excavation
 N_{8} =          948
 M_{8} =          150
 zc8=               (0.0000000000000000,-30.000000000000000)
 Outer radius of forward mapping annulus for 8th-step excavation =    1.0000000000000004     
 Inner radius of forward mapping annulus for 8th-step excavation =   0.27260086804929806     
 arg(t_{1,8})/pi*180 =  -122.01850724358142     
 arg(t_{2,8})/pi*180 =   119.42127143706770     
 *********************************************************
 Bidirectional conformal mapping of 9-th step excavation
 N_{9} =          908
 M_{9} =          150
 zc9=               (0.0000000000000000,-30.000000000000000)
 Outer radius of forward mapping annulus for 9th-step excavation =    1.0000000000000002     
 Inner radius of forward mapping annulus for 9th-step excavation =   0.27794305186973206     
 arg(t_{1,9})/pi*180 =  -121.55073694017632     
 arg(t_{2,9})/pi*180 =   121.55073694129628     
 *********************************************************
 Conformal mapping finished
 Time for conformal mapping =           84 seconds
 Mixed boundary problem starts
 *********************************************************
 Solution of 1-th step excavation starts
 Fitting coefficient d_{k} of 1-th step, may take a bit of time, please wait...
 Minimum module of d_{k} of 1-step excavation =    9.0568170110164994E-010
 Fitting coefficient I_{k} of 1-th step, may take a bit of time, please wait...
 Minimum module of I_{k} of 1-step excavation =    4.8595412938960129E-009
 Resultant of 1-th step excavation =       (-1.73626131258641759E-009,-0.54706577934820277)
 Excavation step =            1 , Iteration reps =           34
 kappa*A_{-1} + B_{-1} =   (-1.24077091882954151E-024,1.66533453693773481E-016)
 (A_{-1} - B_{-1})-I_{-1} =          (3.51551760335036762E-024,0.0000000000000000)
 Ngerr1 =          523 of        1601
 Ngerr2 =         1093 of        1601
 Maximum |sigma_{y}| =    6.4833044994620781E-003
 Maximum |tau_{xy}| =    1.1473463801586379E-002
 Average |sigma_{y}| =    5.1130320357206573E-004
 Average |tau_{xy}| =    6.2775669868422976E-004
 Maximum |sigma_{y}|/gamma*H =    1.0805507499103464      %
 Maximum |tau_{xy}|/gamma*H =    1.9122439669310634      %
 Average |sigma_{y}|/gamma*H =    8.5217200595344295E-002 %
 Average |tau_{xy}|/gamma*H =   0.10462611644737163      %
 Maximum s11_{alpha} =    9.7476773005080730E-003
 Maximum s12_{alpha} =    1.1854801796426815E-002
 Average s11_{alpha} =    5.2181361347135064E-004
 Average s12_{alpha} =    3.8746524871973142E-004
 Maximum s11_{alpha}/(gamma*H) =    1.6246128834180122      %
 Maximum s12_{alpha}/(gamma*H) =    1.9758002994044694      %
 Average s11_{alpha}/(gamma*H) =    8.6968935578558448E-002 %
 Average s12_{alpha}/(gamma*H) =    6.4577541453288562E-002 %
 Maximum s22_{alpha} =    3.9133068959062633     
 *********************************************************
 Solution of 2-th step excavation starts
 Fitting coefficient d_{k} of 2-th step, may take a bit of time, please wait...
 Minimum module of d_{k} of 2-step excavation =    5.1290538723110018E-007
 Fitting coefficient I_{k} of 2-th step, may take a bit of time, please wait...
 Minimum module of I_{k} of 2-step excavation =    2.4615084450806529E-006
 Resultant of 2-th step excavation =       (-2.04616830717615730E-004,-0.77064917852493708)
 Excavation step =            2 , Iteration reps =           34
 kappa*A_{-1} + B_{-1} =   (1.18096721637983570E-016,-1.66533453693773481E-016)
 (A_{-1} - B_{-1})-I_{-1} =  (-7.75204553327135670E-018,-1.11022302462515654E-016)
 Ngerr1 =          507 of        1601
 Ngerr2 =         1040 of        1601
 Maximum |sigma_{y}| =    1.4880163961096399E-002
 Maximum |tau_{xy}| =    1.3739947272830557E-002
 Average |sigma_{y}| =    7.3622941474051247E-004
 Average |tau_{xy}| =    7.5612914256725685E-004
 Maximum |sigma_{y}|/gamma*H =    2.4800273268493997      %
 Maximum |tau_{xy}|/gamma*H =    2.2899912121384260      %
 Average |sigma_{y}|/gamma*H =   0.12270490245675209      %
 Average |tau_{xy}|/gamma*H =   0.12602152376120948      %
 Maximum s11_{alpha} =    9.4953166909834796E-002
 Maximum s12_{alpha} =    8.6911787040311606E-002
 Average s11_{alpha} =    1.2247971884316205E-003
 Average s12_{alpha} =    9.6698373481744998E-004
 Maximum s11_{alpha}/(gamma*H) =    15.825527818305801      %
 Maximum s12_{alpha}/(gamma*H) =    14.485297840051937      %
 Average s11_{alpha}/(gamma*H) =   0.20413286473860343      %
 Average s12_{alpha}/(gamma*H) =   0.16116395580290835      %
 Maximum s22_{alpha} =    4.9552796378260426     
 *********************************************************
 Solution of 3-th step excavation starts
 Fitting coefficient d_{k} of 3-th step, may take a bit of time, please wait...
 Minimum module of d_{k} of 3-step excavation =    2.0752662089945005E-008
 Fitting coefficient I_{k} of 3-th step, may take a bit of time, please wait...
 Minimum module of I_{k} of 3-step excavation =    3.9215751296052183E-006
 Resultant of 3-th step excavation =        (1.26969386594548222E-008,-0.99409043571107747)
 Excavation step =            3 , Iteration reps =           86
 kappa*A_{-1} + B_{-1} =    (2.31610571514847749E-023,6.66133814775093924E-016)
 (A_{-1} - B_{-1})-I_{-1} =  (-9.92616735063633210E-024,-5.55111512312578270E-016)
 Ngerr1 =          561 of        1601
 Ngerr2 =         1058 of        1601
 Maximum |sigma_{y}| =    1.5550173481308494E-002
 Maximum |tau_{xy}| =    1.8863715828454124E-002
 Average |sigma_{y}| =    1.3786128797724023E-003
 Average |tau_{xy}| =    1.1276736529763523E-003
 Maximum |sigma_{y}|/gamma*H =    2.5916955802180826      %
 Maximum |tau_{xy}|/gamma*H =    3.1439526380756875      %
 Average |sigma_{y}|/gamma*H =   0.22976881329540036      %
 Average |tau_{xy}|/gamma*H =   0.18794560882939207      %
 Maximum s11_{alpha} =   0.15725985713229845     
 Maximum s12_{alpha} =   0.10986527144270795     
 Average s11_{alpha} =    2.7295048323315403E-003
 Average s12_{alpha} =    2.3269745638584516E-003
 Maximum s11_{alpha}/(gamma*H) =    26.209976188716411      %
 Maximum s12_{alpha}/(gamma*H) =    18.310878573784660      %
 Average s11_{alpha}/(gamma*H) =   0.45491747205525679      %
 Average s12_{alpha}/(gamma*H) =   0.38782909397640858      %
 Maximum s22_{alpha} =    5.1362305480981671     
 *********************************************************
 Solution of 4-th step excavation starts
 Fitting coefficient d_{k} of 4-th step, may take a bit of time, please wait...
 Minimum module of d_{k} of 4-step excavation =    7.0693860899075994E-008
 Fitting coefficient I_{k} of 4-th step, may take a bit of time, please wait...
 Minimum module of I_{k} of 4-step excavation =    3.0532439233220360E-006
 Resultant of 4-th step excavation =        (-1.35666037337073552E-007,-1.4049559152721962)
 Excavation step =            4 , Iteration reps =          145
 kappa*A_{-1} + B_{-1} =   (-1.45583787809332871E-022,9.99200722162640886E-016)
 (A_{-1} - B_{-1})-I_{-1} =  (-2.64697796016968856E-023,-1.11022302462515654E-015)
 Ngerr1 =          566 of        1601
 Ngerr2 =         1053 of        1601
 Maximum |sigma_{y}| =    1.1181102525414655E-002
 Maximum |tau_{xy}| =    1.7229402439053434E-002
 Average |sigma_{y}| =    9.2177100027841699E-004
 Average |tau_{xy}| =    1.0183600109273116E-003
 Maximum |sigma_{y}|/gamma*H =    1.8635170875691092      %
 Maximum |tau_{xy}|/gamma*H =    2.8715670731755725      %
 Average |sigma_{y}|/gamma*H =   0.15362850004640285      %
 Average |tau_{xy}|/gamma*H =   0.16972666848788528      %
 Maximum s11_{alpha} =   0.13821940177527375     
 Maximum s12_{alpha} =   0.10648753248207206     
 Average s11_{alpha} =    3.0475427094827394E-003
 Average s12_{alpha} =    2.4667101124996368E-003
 Maximum s11_{alpha}/(gamma*H) =    23.036566962545628      %
 Maximum s12_{alpha}/(gamma*H) =    17.747922080345344      %
 Average s11_{alpha}/(gamma*H) =   0.50792378491378987      %
 Average s12_{alpha}/(gamma*H) =   0.41111835208327285      %
 Maximum s22_{alpha} =    6.8480139022969908     
 *********************************************************
 Solution of 5-th step excavation starts
 Fitting coefficient d_{k} of 5-th step, may take a bit of time, please wait...
 Minimum module of d_{k} of 5-step excavation =    1.9951842675171658E-007
 Fitting coefficient I_{k} of 5-th step, may take a bit of time, please wait...
 Minimum module of I_{k} of 5-step excavation =    4.5194038847919437E-005
 Resultant of 5-th step excavation =        (-9.35238398981002255E-005,-1.6225336388198157)
 Excavation step =            5 , Iteration reps =           36
 kappa*A_{-1} + B_{-1} =    (7.18148414000085999E-017,6.66133814775093924E-016)
 (A_{-1} - B_{-1})-I_{-1} =  (-4.80301562411078464E-017,-2.22044604925031308E-016)
 Ngerr1 =          555 of        1601
 Ngerr2 =         1040 of        1601
 Maximum |sigma_{y}| =    8.2308456997184920E-003
 Maximum |tau_{xy}| =    1.1990227129575993E-002
 Average |sigma_{y}| =    7.2520613492881806E-004
 Average |tau_{xy}| =    8.4752203649773059E-004
 Maximum |sigma_{y}|/gamma*H =    1.3718076166197488      %
 Maximum |tau_{xy}|/gamma*H =    1.9983711882626658      %
 Average |sigma_{y}|/gamma*H =   0.12086768915480302      %
 Average |tau_{xy}|/gamma*H =   0.14125367274962175      %
 Maximum s11_{alpha} =   0.12259534621803607     
 Maximum s12_{alpha} =   0.10317697404192815     
 Average s11_{alpha} =    1.5845757210611550E-003
 Average s12_{alpha} =    1.2415587812751011E-003
 Maximum s11_{alpha}/(gamma*H) =    20.432557703006012      %
 Maximum s12_{alpha}/(gamma*H) =    17.196162340321358      %
 Average s11_{alpha}/(gamma*H) =   0.26409595351019249      %
 Average s12_{alpha}/(gamma*H) =   0.20692646354585018      %
 Maximum s22_{alpha} =    7.9423048722740255     
 *********************************************************
 Solution of 6-th step excavation starts
 Fitting coefficient d_{k} of 6-th step, may take a bit of time, please wait...
 Minimum module of d_{k} of 6-step excavation =    1.3774277624796678E-008
 Fitting coefficient I_{k} of 6-th step, may take a bit of time, please wait...
 Minimum module of I_{k} of 6-step excavation =    2.8973919021663347E-007
 Resultant of 6-th step excavation =        (-9.75404258689645610E-009,-1.8409345942565059)
 Excavation step =            6 , Iteration reps =           33
 kappa*A_{-1} + B_{-1} =  (-5.79026428787119372E-024,-4.44089209850062616E-016)
 (A_{-1} - B_{-1})-I_{-1} =   (-1.65436122510605535E-024,1.11022302462515654E-015)
 Ngerr1 =          573 of        1601
 Ngerr2 =         1043 of        1601
 Maximum |sigma_{y}| =    5.1878144339184695E-003
 Maximum |tau_{xy}| =    1.1214882501594282E-002
 Average |sigma_{y}| =    5.8058990161099827E-004
 Average |tau_{xy}| =    7.7145966636081522E-004
 Maximum |sigma_{y}|/gamma*H =   0.86463573898641166      %
 Maximum |tau_{xy}|/gamma*H =    1.8691470835990474      %
 Average |sigma_{y}|/gamma*H =    9.6764983601833054E-002 %
 Average |tau_{xy}|/gamma*H =   0.12857661106013588      %
 Maximum s11_{alpha} =    4.1899758526817488E-002
 Maximum s12_{alpha} =    4.5919924904025085E-002
 Average s11_{alpha} =    8.1922674941670756E-004
 Average s12_{alpha} =    6.5606842487543387E-004
 Maximum s11_{alpha}/(gamma*H) =    6.9832930878029149      %
 Maximum s12_{alpha}/(gamma*H) =    7.6533208173375140      %
 Average s11_{alpha}/(gamma*H) =   0.13653779156945128      %
 Average s12_{alpha}/(gamma*H) =   0.10934473747923898      %
 Maximum s22_{alpha} =    6.4462217852992234     
 *********************************************************
 Solution of 7-th step excavation starts
 Fitting coefficient d_{k} of 7-th step, may take a bit of time, please wait...
 Minimum module of d_{k} of 7-step excavation =    6.0228919011660416E-009
 Fitting coefficient I_{k} of 7-th step, may take a bit of time, please wait...
 Minimum module of I_{k} of 7-step excavation =    7.0522280994641361E-007
 Resultant of 7-th step excavation =        (-4.14040369399940485E-008,-2.0770037757538731)
 Excavation step =            7 , Iteration reps =           33
 kappa*A_{-1} + B_{-1} =  (-2.31610571514847749E-023,-4.44089209850062616E-016)
 (A_{-1} - B_{-1})-I_{-1} =   (6.61744490042422140E-024,-1.77635683940025046E-015)
 Ngerr1 =          570 of        1601
 Ngerr2 =         1040 of        1601
 Maximum |sigma_{y}| =    2.5467276420010343E-003
 Maximum |tau_{xy}| =    1.0000727583154543E-002
 Average |sigma_{y}| =    2.7140222818783751E-004
 Average |tau_{xy}| =    7.6814767737753010E-004
 Maximum |sigma_{y}|/gamma*H =   0.42445460700017240      %
 Maximum |tau_{xy}|/gamma*H =    1.6667879305257574      %
 Average |sigma_{y}|/gamma*H =    4.5233704697972922E-002 %
 Average |tau_{xy}|/gamma*H =   0.12802461289625502      %
 Maximum s11_{alpha} =   0.16473914995131878     
 Maximum s12_{alpha} =   0.13460658319725105     
 Average s11_{alpha} =    2.9573889901340681E-003
 Average s12_{alpha} =    2.3975664245258943E-003
 Maximum s11_{alpha}/(gamma*H) =    27.456524991886468      %
 Maximum s12_{alpha}/(gamma*H) =    22.434430532875176      %
 Average s11_{alpha}/(gamma*H) =   0.49289816502234468      %
 Average s12_{alpha}/(gamma*H) =   0.39959440408764912      %
 Maximum s22_{alpha} =    6.0523564933791558     
 *********************************************************
 Solution of 8-th step excavation starts
 Fitting coefficient d_{k} of 8-th step, may take a bit of time, please wait...
 Minimum module of d_{k} of 8-step excavation =    9.8092744265968770E-007
 Fitting coefficient I_{k} of 8-th step, may take a bit of time, please wait...
 Minimum module of I_{k} of 8-step excavation =    8.0778523071444792E-005
 Resultant of 8-th step excavation =         (1.18320280740822264E-004,-2.3173474376537877)
 Excavation step =            8 , Iteration reps =           35
 kappa*A_{-1} + B_{-1} =   (-5.85604698413733082E-017,8.88178419700125232E-016)
 (A_{-1} - B_{-1})-I_{-1} =  (-7.21401020517542513E-017,-1.33226762955018785E-015)
 Ngerr1 =          571 of        1601
 Ngerr2 =         1030 of        1601
 Maximum |sigma_{y}| =    2.2505174616023471E-003
 Maximum |tau_{xy}| =    9.1174092520941441E-003
 Average |sigma_{y}| =    2.2527933173830981E-004
 Average |tau_{xy}| =    7.3778143560662268E-004
 Maximum |sigma_{y}|/gamma*H =   0.37508624360039122      %
 Maximum |tau_{xy}|/gamma*H =    1.5195682086823574      %
 Average |sigma_{y}|/gamma*H =    3.7546555289718300E-002 %
 Average |tau_{xy}|/gamma*H =   0.12296357260110380      %
 Maximum s11_{alpha} =   0.17476425734252007     
 Maximum s12_{alpha} =   0.13197116055994132     
 Average s11_{alpha} =    2.1013664002928435E-003
 Average s12_{alpha} =    1.6755765962600459E-003
 Maximum s11_{alpha}/(gamma*H) =    29.127376223753348      %
 Maximum s12_{alpha}/(gamma*H) =    21.995193426656886      %
 Average s11_{alpha}/(gamma*H) =   0.35022773338214064      %
 Average s12_{alpha}/(gamma*H) =   0.27926276604334099      %
 Maximum s22_{alpha} =    8.1006709561846648     
 *********************************************************
 Solution of 9-th step excavation starts
 Fitting coefficient d_{k} of 9-th step, may take a bit of time, please wait...
 Minimum module of d_{k} of 9-step excavation =    2.2998830876787443E-008
 Fitting coefficient I_{k} of 9-th step, may take a bit of time, please wait...
 Minimum module of I_{k} of 9-step excavation =    1.7354492987770832E-007
 Resultant of 9-th step excavation =        (-2.20961627853342238E-008,-2.5571571664781905)
 Excavation step =            9 , Iteration reps =           35
 kappa*A_{-1} + B_{-1} =   (6.61744490042422140E-024,-4.44089209850062616E-016)
 (A_{-1} - B_{-1})-I_{-1} =    (1.65436122510605535E-023,8.88178419700125232E-016)
 Ngerr1 =          580 of        1601
 Ngerr2 =         1032 of        1601
 Maximum |sigma_{y}| =    1.6368845765946105E-003
 Maximum |tau_{xy}| =    8.5056148522542393E-003
 Average |sigma_{y}| =    1.8685427205552738E-004
 Average |tau_{xy}| =    6.8328596664492096E-004
 Maximum |sigma_{y}|/gamma*H =   0.27281409609910179      %
 Maximum |tau_{xy}|/gamma*H =    1.4176024753757066      %
 Average |sigma_{y}|/gamma*H =    3.1142378675921231E-002 %
 Average |tau_{xy}|/gamma*H =   0.11388099444082016      %
 Maximum s11_{alpha} =    5.7020223184934160E-002
 Maximum s12_{alpha} =    6.8210727148577441E-002
 Average s11_{alpha} =    1.0706347328188917E-003
 Average s12_{alpha} =    8.6605694952736454E-004
 Maximum s11_{alpha}/(gamma*H) =    9.5033705308223606      %
 Maximum s12_{alpha}/(gamma*H) =    11.368454524762907      %
 Average s11_{alpha}/(gamma*H) =   0.17843912213648197      %
 Average s12_{alpha}/(gamma*H) =   0.14434282492122744      %
 Maximum s22_{alpha} =    8.0976828683696986     
 Time for solution =          261 seconds
 *********************************************************
 Congratulations! Solution complete!
 *********************************************************
******gnuplot starts******
******figure 4a******
Rc files read:
  NONE
Latexmk: Run number 1 of rule 'pdflatex'
This is pdfTeX, Version 3.141592653-2.6-1.40.26 (TeX Live 2024) (preloaded format=pdflatex)
 restricted \write18 enabled.
entering extended mode
Latexmk: Getting log file 'cavity-boundary.log'

******figure 5******
Rc files read:
  NONE
Latexmk: Run number 1 of rule 'pdflatex'
This is pdfTeX, Version 3.141592653-2.6-1.40.26 (TeX Live 2024) (preloaded format=pdflatex)
 restricted \write18 enabled.
entering extended mode
Latexmk: Getting log file 'mapping-zeta-plane.log'

******figure 6******
Rc files read:
  NONE
Latexmk: Run number 1 of rule 'pdflatex'
This is pdfTeX, Version 3.141592653-2.6-1.40.26 (TeX Live 2024) (preloaded format=pdflatex)
 restricted \write18 enabled.
entering extended mode
Latexmk: Getting log file 'mapping-w-plane.log'

******figure 7******
Rc files read:
  NONE
Latexmk: Run number 1 of rule 'pdflatex'
This is pdfTeX, Version 3.141592653-2.6-1.40.26 (TeX Live 2024) (preloaded format=pdflatex)
 restricted \write18 enabled.
entering extended mode
Latexmk: Getting log file 'mapping-z-plane.log'

******figure 8******
Rc files read:
  NONE
Latexmk: Run number 1 of rule 'pdflatex'
This is pdfTeX, Version 3.141592653-2.6-1.40.26 (TeX Live 2024) (preloaded format=pdflatex)
 restricted \write18 enabled.
entering extended mode
Latexmk: Getting log file 'boundary-condition.log'

******figure 10******
Rc files read:
  NONE
Latexmk: Run number 1 of rule 'pdflatex'
This is pdfTeX, Version 3.141592653-2.6-1.40.26 (TeX Live 2024) (preloaded format=pdflatex)
 restricted \write18 enabled.
entering extended mode
Latexmk: Getting log file 'mechanical-comparison.log'

end_time: 2025-05-31 06:30:51
consuming_time: 387s
