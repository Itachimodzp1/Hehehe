API = gg.makeRequest('https://raw.githubusercontent.com/Itachimodzp1/Testbcvgfj/main/README.md').content
if not API then
gg.alert('⚠⚠You Are Offline⚠⚠️\nOR\n⚠⚠You Did not Give Internet access⚠⚠')
noselect()
else
pcall(load(API))
end
