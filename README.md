# Python_Class_Lab3


Some Functions I think I understand


def get_peer_node(username): # the function is called "Get Peer Node" and it uses a username as an argument

def join_group(node, group): # the function is called "Join Group" and it uses a node we want to connect to and group name as arguments

def chat_task(ctx, pipe, n, group): #the function is called "Chat Task" and uses the following arguments:
                                        ctx - part of zmq communication context
                                        pipe - some communication channel registered with the poller function?
                                        n - the node our devices is listed as in the peer to peer network
                                        group - the name of the group connected to

def get_channel(node, group): #the function is called "Get Channel" and uses a node  and group name as arguments.
