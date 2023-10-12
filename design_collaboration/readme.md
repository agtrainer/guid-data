shared design collaboration model directories
Because this is an unreleased design, the major digit on the rev string is 0.
Each iteration is in its own subdirectory for management.
Design collaboration revised the iteration number of the rev.
Reference rec_prac_PID document for details.

State of model shown be each revision:

Rev 0.0: initial design

Rev 0.1: Keep cartesian_point instance but change coordinates

Rev 0.2: Delete the point and create a new point

Rev 0.3: Delete the hole and create a new hole at a new location

Rev 0.4: Add a chamfer to a corner. 



---------------------------------------------------------
Rosemary Astheimers 's "NX_Plate_w_Hole" files, Revs 0.0, 0.1, 0.2, 0.3, and 0.4 that have been annotated with additional label information on certain entities (*.LBLS_*.stp) to facilitate generation of type 5 UUIDs for those entities (see below) -

	product, pmi, certain topological entities

Above files run through Ed Paff's stepuuid2.exe utility to include UUIDs at the end of the data section (*_UUIDS_*.stp).

Above UUID files run through Ed Paff's stepuuid2.exe utility with the "-v" option to produce verification files (*_UUIDS_*_chk.txt).  These verification files confirm each UUID generated and the entity to which the UUID is assigned (either directly or indirectly).

Please contact Asa Trainer (agtrainer@comcast.net) if you have any questions.

Thanks!
