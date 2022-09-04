## YAMS - Yet Another MS20-style VCF

My take on the MS20 voltage-controlled filter - if you want squally, resonant acid sounds then this may well be right up your alley.

Built around an LM13700 transconductance amplifier, this filter uses a pair of red LEDs in the feedback path (rather than the string
of diodes in the original Korg design) to make things a little more ... interesting, but other than that it's a straight-up lifting of 
the classic MS20 design.

Has both low-pass and high-pass inputs, which should be pretty self-explanatory and there's nothing at all to stop you using them both 
together (hilarity often ensues here, since you'll get a really screwed-up bandpass-style response).

### Build notes

* Two LEDs replace the diode string in the feedback loop; for best results, use LEDs with as low a forward voltage as possible. Avoid high-brightness LEDs.
* R22 and R25 limit the amount of current entering circuit via the resonance pot. 47k is a representative value - anything between 33k and 56k will work.
* C2, C5 and C8 are the filter capacitors - 1nF mirrors the original design; use larger values to 'soften' the response although anything over 3.3nF will sound a bit muddy.
