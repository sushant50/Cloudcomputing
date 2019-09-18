Tasks for Swift


1. check your python version must >= 2.6

2. `yum install libvirt`

3. `yum install memcached`

4. `yum install xfsprogs`

5. `yum install python-setuptools python-devel python-simplejson python-config`

6. `easy_install webob`

7. ~~easy_install eventlet~~

8. Install pip using- `yum install pip`

9. Install setup tools using- `pip install setuptools`

10. Run `easy_install eventlet`

11. ~~install xattr-0.6.2.tar.gz, python setup.py build, python setup.py install~~

12. `pip install xattr`

13. ~~install coverage-3.5.1.tar.gz, python setup.py build, python setup.py install~~

14. `pip install coverage`

15. ~~wget "http://www.openstack.org/projects/storage/latest-release/"~~

      ~~python setup.py build~~

      ~~python setup.py install

16. wget "https://launchpad.net/swift/essex/1.4.8/+download/swift-1.4.8.tar.gz"

        tar -xvf swift-1.4.8 
        
        cd swift-1.4.8
        
        python setup.py build

        python setup.py install

17. ~~wget "https://github.com/downloads/gholt/swauth/swauth-lucid-build-1.0.2-1.tgz"~~

       ~~python setup.py build~~

       ~~python setup.py install~~
       
18. `pip install swauth`

19. `mkdir /etc/swift`

20. `yum install openssh-server`

21. `yum install git-core`

22. `vi /etc/swift/swift.conf`

23. [swift-hash]


    swift_hash_path_suffix = `od -t x8 -N 8 -A n </dev/random` 
    
24. `cd /etc/swift/`

25. `openssl req -new -x509 -nodes -out cert.crt -keyout cert.key`

26. `service memcached restart`

27. `ps -aux | grep mem`

28. `easy_install netifaces`

29. `vi /etc/swift/proxy-server.conf
`
