# rpiadmin


A Python admin console web application for the Raspberry Pi.

### Components

Flask web server/admin panel with safe shutdown, reboot, system stats, etc. (in progress)

ROM import for use with RetroPie (in progress)

## Install

    git clone
    cd rpiadmin
    virtualenv venv
    . venv/bin/activate
    pip install -r requirements.txt

## Running

Use the environment variable RPI_ENV if you want the system calls to work (only makes sense on a Raspberry Pi).

    RPI_ENV=production python rpiadmin.py
    
## License

This program is free software: you can redistribute it and/or modify
it under the terms of the GNU General Public License as published by
the Free Software Foundation, either version 3 of the License, or
(at your option) any later version.

This program is distributed in the hope that it will be useful,
but WITHOUT ANY WARRANTY; without even the implied warranty of
MERCHANTABILITY or FITNESS FOR A PARTICULAR PURPOSE.  See the
GNU General Public License for more details.

You should have received a copy of the GNU General Public License
along with this program.  If not, see <http://www.gnu.org/licenses/>.

    
