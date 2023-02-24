Photo-Meta
==========

$photometa = PhotoMetaData("/img/myphoto.jpg");

echo "Used: " . $photometa['make'] . " " . $photometa['model'] . "<br />";
echo "Exposure Time: " . $photometa['exposure'] . "<br />";
echo "Aperture: " . $photometa['aperture'] . "<br />";
echo "ISO: " . $photometa['iso'] . "<br />";
echo "Date Taken: " . $photometa['date'] . "<br />";