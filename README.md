# FFI_poroelasticity
The code is used to calculate the poroelastic Green's function in the FFI

#fault_file is a matrix that defines the model parameters:

1 X(Ref) of each rectangular patch (East is positive) %m

2 Y(Ref) of each rectangular patch (North is positive) %m

3 Z(Ref) of each rectangular patch (Down is positive) %m

4 Strike angle of each patch

5 Dip angle of each patch

6 Along-strike length of each patch %m

7 Down-dip length of each patch %m


#insardata_file is a matrix that defines the model parameters:

1 X(Ref) of each rectangular patch (East is positive) %m

2 Y(Ref) of each rectangular patch (North is positive) %m

3 Los displacement %m

4 Los_E displacement

5 Los_S displacement

6 Los_U displacement


#independent green function file is calculated by Zhou et al.(2023)
