#Namespace prefix location

If using MDeval.XMLeval returns an empty evaluation for concepts, investigate if one of these namespaces is used. If it is(they are), use the listed location along with the MDeval.normalizeNamespace function. Removing the ":prefix" from the string will align the default namespace of the record(s).

### ISO 19115-2
gco:xmlns:gco="http://www.isotc211.org/2005/gco" 
xmlns:gmd="http://www.isotc211.org/2005/gmd" 
xmlns:gmx="http://www.isotc211.org/2005/gmx" 
xmlns:gmi="http://www.isotc211.org/2005/gmi" 
xmlns:gts="http://www.isotc211.org/2005/gts" 
xmlns:gml="http://www.opengis.net/gml/3.2" 
xmlns:srv="http://www.isotc211.org/2005/srv"

### ISO 19115-1
xmlns:cat="http://standards.iso.org/iso/19115/-3/cat/1.0" 
xmlns:mrl="http://standards.iso.org/iso/19115/-3/mrl/1.0" 
xmlns:mcc="http://standards.iso.org/iso/19115/-3/mcc/1.0" 
xmlns:mpc="http://standards.iso.org/iso/19115/-3/mpc/1.0" 
xmlns:mri="http://standards.iso.org/iso/19115/-3/mri/1.0" 
xmlns:mac="http://standards.iso.org/iso/19115/-3/mac/1.0" 
xmlns:mrs="http://standards.iso.org/iso/19115/-3/mrs/1.0" 
xmlns:mco="http://standards.iso.org/iso/19115/-3/mco/1.0"   
xmlns:lan="http://standards.iso.org/iso/19115/-3/lan/1.0" 
xmlns:cit="http://standards.iso.org/iso/19115/-3/cit/1.0" 
xmlns:mas="http://standards.iso.org/iso/19115/-3/mas/1.0" 
xmlns:mda="http://standards.iso.org/iso/19115/-3/mda/1.0" 
xmlns:msr="http://standards.iso.org/iso/19115/-3/msr/1.0" 
xmlns:mdb="http://standards.iso.org/iso/19115/-3/mdb/1.0" 
xmlns:gex="http://standards.iso.org/iso/19115/-3/gex/1.0" 
xmlns:gcx="http://standards.iso.org/iso/19115/-3/gcx/1.0"  
xmlns:mex="http://standards.iso.org/iso/19115/-3/mex/1.0" 
xmlns:mdq="http://standards.iso.org/iso/19115/-3/mdq/1.0" 
xmlns:mmi="http://standards.iso.org/iso/19115/-3/mmi/1.0" 
xmlns:mdt="http://standards.iso.org/iso/19115/-3/mdt/1.0" 
xmlns:mds="http://standards.iso.org/iso/19115/-3/mds/1.0" 
xmlns:mrc="http://standards.iso.org/iso/19115/-3/mrc/1.0" 
xmlns:mrd="http://standards.iso.org/iso/19115/-3/mrd/1.0" 
xmlns:mai="http://standards.iso.org/iso/19115/-3/mai/1.0" 

### NASA
xmlns:dif="http://gcmd.gsfc.nasa.gov/Aboutus/xml/dif/" 
xmlns:echo="http://www.echo.nasa.gov/ingest/schemas/operations/" 
xmlns:eos="http://earthdata.nasa.gov/schema/eos" 
xmlns:serf="http://gcmd.gsfc.nasa.gov/xml/serf" 

### FGDC
xmlns:csdgm="http://www.fgdc.gov/metadata/csdgm"
xmlns:mercury="http://purl.org/ornl/schema/mercury/terms/v1.0" 
xmlns:bdp="https://www.fgdc.gov/standards/projects/FGDC-standards-projects/metadata/biometadata" 

### DublinCore
xmlns:dcterms="http://purl.org/dc/terms/" 
xmlns:dc="http://purl.org/dc/elements/1.1/" 

xmlns:onedcx="http://ns.dataone.org/metadata/schema/onedcx/v1.0" 

### MODS
xmlns:mods="https://www.loc.gov/standards/mods/v3/mods-3-6.xsd"  

### DataCite
xmlns:dcite="http://datacite.org/schema/kernel-3" 

### Dryad  
xmlns:dryad="http://purl.org/dryad/schema/terms/v3.1" 

### DarwinCore
xmlns:dwc="http://rs.tdwg.org/dwc/terms/" 

### EML
xmlns:eml="eml://ecoinformatics.org/eml-2.1.1" 

### NCAR-RDA
xmlns:rda="http://rda.ucar.edu/schemas/common.xsd" 
