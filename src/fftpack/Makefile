include ../../make.inc

OBJS=c1f2kb.o c1f2kf.o c1f3kb.o c1f3kf.o c1f4kb.o c1f4kf.o c1f5kb.o c1f5kf.o c1fgkb.o c1fgkf.o c1fm1b.o c1fm1f.o cfft1b.o cfft1f.o cfft1i.o cfft2b.o cfft2f.o cfft2i.o cfftmb.o cfftmf.o cfftmi.o cmf2kb.o cmf2kf.o cmf3kb.o cmf3kf.o cmf4kb.o cmf4kf.o cmf5kb.o cmf5kf.o cmfgkb.o cmfgkf.o cmfm1b.o cmfm1f.o cosq1b.o cosq1f.o cosq1i.o cosqb1.o cosqf1.o cosqmb.o cosqmf.o cosqmi.o cost1b.o cost1f.o cost1i.o costb1.o costf1.o costmb.o costmf.o costmi.o mcsqb1.o mcsqf1.o mcstb1.o mcstf1.o mradb2.o mradb3.o mradb4.o mradb5.o mradbg.o mradf2.o mradf3.o mradf4.o mradf5.o mradfg.o mrftb1.o mrftf1.o mrfti1.o msntb1.o msntf1.o r1f2kb.o r1f2kf.o r1f3kb.o r1f3kf.o r1f4kb.o r1f4kf.o r1f5kb.o r1f5kf.o r1fgkb.o r1fgkf.o r2w.o r8_factor.o r8_mcfti1.o r8_tables.o rfft1b.o rfft1f.o rfft1i.o rfft2b.o rfft2f.o rfft2i.o rfftb1.o rfftf1.o rffti1.o rfftmb.o rfftmf.o rfftmi.o sinq1b.o sinq1f.o sinq1i.o sinqmb.o sinqmf.o sinqmi.o sint1b.o sint1f.o sint1i.o sintb1.o  sintf1.o sintmb.o sintmf.o sintmi.o w2r.o xercon.o xerfft.o


.SUFFIXES:.f90 .f


lib: ${OBJS}

.f90.o:	
	$(FC) -c $(FCOPT) $(MOPT)../ $< -o ../$@

.f.o:	
	$(FC) -c $(FCOPT) $< -o ../$@

clean:
	rm -fv *.o *.mod
