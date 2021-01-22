# transceiver-bladerf
transceiver-bladerf for openbts
git clone https://github.com/Keskebeu/transceiver-bladerf.git
cd transceiver-bladerf
sudo chmod +x transceiver-bladerf
cp transceiver-bladerf /dir/to/openbts/apps
ln -sf transceiver-bladerf transceiver

### The Other two files are not a nessecity, they are patched for the revision 507 of yatebts in case to build the transceiver again. The downloaded files have to be replaced to the mbts/TransceiverRAD1 directory.
