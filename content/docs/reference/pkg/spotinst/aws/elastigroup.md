
---
title: "Elastigroup"
block_external_search_index: true
---






## Create a Elastigroup Resource

{{< chooser language "javascript,typescript,python,go,csharp" / >}}

{{% choosable language nodejs %}}
<div class="highlight"><pre class="chroma"><code class="language-typescript" data-lang="typescript"><span class="k">new </span><span class="nx"><a href="/docs/reference/pkg/nodejs/pulumi/spotinst/aws/#Elastigroup">Elastigroup</a></span><span class="p">(</span><span class="nx">name</span>: <span class="nx"><a href="https://developer.mozilla.org/en-US/docs/Web/JavaScript/Reference/Global_Objects/string">string</a></span><span class="p">, </span><span class="nx">args</span>: <span class="nx"><a href="/docs/reference/pkg/nodejs/pulumi/spotinst/aws/#ElastigroupArgs">ElastigroupArgs</a></span><span class="p">, </span><span class="nx">opts</span>?: <span class="nx"><a href="/docs/reference/pkg/nodejs/pulumi/pulumi/#CustomResourceOptions">pulumi.CustomResourceOptions</a></span><span class="p">);</span></code></pre></div>
{{% /choosable %}}

{{% choosable language python %}}
<div class="highlight"><pre class="chroma"><code class="language-python" data-lang="python"><span class="k">def </span><span class="nf">Elastigroup</span><span class="p">(resource_name, opts=None, </span>availability_zones=None<span class="p">, </span>block_devices_mode=None<span class="p">, </span>capacity_unit=None<span class="p">, </span>cpu_credits=None<span class="p">, </span>description=None<span class="p">, </span>desired_capacity=None<span class="p">, </span>draining_timeout=None<span class="p">, </span>ebs_block_devices=None<span class="p">, </span>ebs_optimized=None<span class="p">, </span>elastic_ips=None<span class="p">, </span>elastic_load_balancers=None<span class="p">, </span>enable_monitoring=None<span class="p">, </span>ephemeral_block_devices=None<span class="p">, </span>fallback_to_ondemand=None<span class="p">, </span>health_check_grace_period=None<span class="p">, </span>health_check_type=None<span class="p">, </span>health_check_unhealthy_duration_before_replacement=None<span class="p">, </span>iam_instance_profile=None<span class="p">, </span>image_id=None<span class="p">, </span>instance_types_ondemand=None<span class="p">, </span>instance_types_preferred_spots=None<span class="p">, </span>instance_types_spots=None<span class="p">, </span>instance_types_weights=None<span class="p">, </span>integration_beanstalk=None<span class="p">, </span>integration_codedeploy=None<span class="p">, </span>integration_docker_swarm=None<span class="p">, </span>integration_ecs=None<span class="p">, </span>integration_gitlab=None<span class="p">, </span>integration_kubernetes=None<span class="p">, </span>integration_mesosphere=None<span class="p">, </span>integration_multai_runtime=None<span class="p">, </span>integration_nomad=None<span class="p">, </span>integration_rancher=None<span class="p">, </span>integration_route53=None<span class="p">, </span>key_name=None<span class="p">, </span>lifetime_period=None<span class="p">, </span>max_size=None<span class="p">, </span>min_size=None<span class="p">, </span>multai_target_sets=None<span class="p">, </span>name=None<span class="p">, </span>network_interfaces=None<span class="p">, </span>ondemand_count=None<span class="p">, </span>orientation=None<span class="p">, </span>persist_block_devices=None<span class="p">, </span>persist_private_ip=None<span class="p">, </span>persist_root_device=None<span class="p">, </span>placement_tenancy=None<span class="p">, </span>preferred_availability_zones=None<span class="p">, </span>private_ips=None<span class="p">, </span>product=None<span class="p">, </span>region=None<span class="p">, </span>revert_to_spot=None<span class="p">, </span>scaling_down_policies=None<span class="p">, </span>scaling_strategies=None<span class="p">, </span>scaling_target_policies=None<span class="p">, </span>scaling_up_policies=None<span class="p">, </span>scheduled_tasks=None<span class="p">, </span>security_groups=None<span class="p">, </span>shutdown_script=None<span class="p">, </span>signals=None<span class="p">, </span>spot_percentage=None<span class="p">, </span>stateful_deallocation=None<span class="p">, </span>subnet_ids=None<span class="p">, </span>tags=None<span class="p">, </span>target_group_arns=None<span class="p">, </span>update_policy=None<span class="p">, </span>user_data=None<span class="p">, </span>utilize_reserved_instances=None<span class="p">, </span>wait_for_capacity=None<span class="p">, </span>wait_for_capacity_timeout=None<span class="p">, __props__=None);</span></code></pre></div>
{{% /choosable %}}

{{% choosable language go %}}
<div class="highlight"><pre class="chroma"><code class="language-go" data-lang="go"><span class="k">func </span>NewElastigroup<span class="p">(</span><span class="nx">ctx</span> *<span class="nx"><a href="https://pkg.go.dev/github.com/pulumi/pulumi/sdk/go/pulumi?tab=doc#Context">pulumi.Context</a></span><span class="p">, </span><span class="nx">name</span> <span class="nx"><a href="https://golang.org/pkg/builtin/#string">string</a></span><span class="p">, </span><span class="nx">args</span> <span class="nx"><a href="https://pkg.go.dev/github.com/pulumi/pulumi-spotinst/sdk/go/spotinst/aws?tab=doc#ElastigroupArgs">ElastigroupArgs</a></span><span class="p">, </span><span class="nx">opts</span> ...<span class="nx"><a href="https://pkg.go.dev/github.com/pulumi/pulumi/sdk/go/pulumi?tab=doc#ResourceOption">pulumi.ResourceOption</a></span><span class="p">) (*<span class="nx"><a href="https://pkg.go.dev/github.com/pulumi/pulumi-spotinst/sdk/go/spotinst/aws?tab=doc#Elastigroup">Elastigroup</a></span>, error)</span></code></pre></div>
{{% /choosable %}}

{{% choosable language csharp %}}
<div class="highlight"><pre class="chroma"><code class="language-csharp" data-lang="csharp"><span class="k">public </span><span class="nx"><a href="/docs/reference/pkg/dotnet/Pulumi.Spotinst/Pulumi.Spotinst.Aws.Elastigroup.html">Elastigroup</a></span><span class="p">(</span><span class="nx"><a href="https://docs.microsoft.com/en-us/dotnet/csharp/language-reference/builtin-types/built-in-types">string</a></span> <span class="nx">name<span class="p">, </span><span class="nx"><a href="/docs/reference/pkg/dotnet/Pulumi.Spotinst/Pulumi.Spotinst.Aws.ElastigroupArgs.html">ElastigroupArgs</a></span> <span class="nx">args<span class="p">, </span><span class="nx"><a href="/docs/reference/pkg/dotnet/Pulumi/Pulumi.CustomResourceOptions.html">CustomResourceOptions</a></span>? <span class="nx">opts = null<span class="p">)</span></code></pre></div>
{{% /choosable %}}

{{% choosable language nodejs %}}

<dl class="resources-properties">
    <dt class="property-required" title="Required">
        <span>name</span>
        <span class="property-indicator"></span>
    </dt>
    <dd>The unique name of the resource.</dd>
    <dt class="property-optional" title="Optional">
        <span>args</span>
        <span class="property-indicator"></span>
    </dt>
    <dd>The arguments to use to populate this resource's properties.</dd>
    <dt class="property-optional" title="Optional">
        <span>opts</span>
        <span class="property-indicator"></span>
    </dt>
    <dd>A bag of options that control this resource's behavior.</dd>
</dl>

{{% /choosable %}}

{{% choosable language python %}}
<dl class="resources-properties">
    <dt class="property-required" title="Required">
        <span>name</span>
        <span class="property-indicator"></span>
    </dt>
    <dd>The unique name of the resource.</dd>
    <dt class="property-optional" title="Optional">
        <span>opts</span>
        <span class="property-indicator"></span>
    </dt>
    <dd>A bag of options that control this resource's behavior.</dd>
</dl>
{{% /choosable %}}

{{% choosable language go %}}

<dl class="resources-properties">
    <dt class="property-required" title="Required">
        <span>name</span>
        <span class="property-indicator"></span>
    </dt>
    <dd>The unique name of the resource.</dd>
    <dt class="property-optional" title="Optional">
        <span>args</span>
        <span class="property-indicator"></span>
    </dt>
    <dd>The arguments to use to populate this resource's properties.</dd>
    <dt class="property-optional" title="Optional">
        <span>opts</span>
        <span class="property-indicator"></span>
    </dt>
    <dd>A bag of options that control this resource's behavior.</dd>
</dl>

{{% /choosable %}}

{{% choosable language csharp %}}

<dl class="resources-properties">
    <dt class="property-required" title="Required">
        <span>name</span>
        <span class="property-indicator"></span>
    </dt>
    <dd>The unique name of the resource.</dd>
    <dt class="property-optional" title="Optional">
        <span>args</span>
        <span class="property-indicator"></span>
    </dt>
    <dd>The arguments to use to populate this resource's properties.</dd>
    <dt class="property-optional" title="Optional">
        <span>opts</span>
        <span class="property-indicator"></span>
    </dt>
    <dd>A bag of options that control this resource's behavior.</dd>
</dl>

{{% /choosable %}}

#### Resource Arguments




{{% choosable language csharp %}}
<dl class="resources-properties">

    <dt class="property-optional"
            title="Optional">
        <span>Availability<wbr>Zones</span>
        <span class="property-indicator"></span>
        <span class="property-type">List<string>?</span>
    </dt>
    <dd>{{% md %}}List of Strings of availability zones. When this parameter is set, `subnet_ids` should be left unused.
Note: `availability_zones` naming syntax follows the convention `availability-zone:subnet:placement-group-name`. For example, to set an AZ in `us-east-1` with subnet `subnet-123456` and placement group `ClusterI03`, you would set:
`availability_zones = ["us-east-1a:subnet-123456:ClusterI03"]`
{{% /md %}}</dd>

    <dt class="property-optional"
            title="Optional">
        <span>Block<wbr>Devices<wbr>Mode</span>
        <span class="property-indicator"></span>
        <span class="property-type">string?</span>
    </dt>
    <dd>{{% md %}}{{% /md %}}</dd>

    <dt class="property-optional"
            title="Optional">
        <span>Capacity<wbr>Unit</span>
        <span class="property-indicator"></span>
        <span class="property-type">string?</span>
    </dt>
    <dd>{{% md %}}The capacity unit to launch instances by. If not specified, when choosing the weight unit, each instance will weight as the number of its vCPUs.
{{% /md %}}</dd>

    <dt class="property-optional"
            title="Optional">
        <span>Cpu<wbr>Credits</span>
        <span class="property-indicator"></span>
        <span class="property-type">string?</span>
    </dt>
    <dd>{{% md %}}Controls how T3 instances are launched. Valid values: `standard`, `unlimited`.
{{% /md %}}</dd>

    <dt class="property-optional"
            title="Optional">
        <span>Description</span>
        <span class="property-indicator"></span>
        <span class="property-type">string?</span>
    </dt>
    <dd>{{% md %}}The group description.
{{% /md %}}</dd>

    <dt class="property-optional"
            title="Optional">
        <span>Desired<wbr>Capacity</span>
        <span class="property-indicator"></span>
        <span class="property-type">int?</span>
    </dt>
    <dd>{{% md %}}The desired number of instances the group should have at any time.
{{% /md %}}</dd>

    <dt class="property-optional"
            title="Optional">
        <span>Draining<wbr>Timeout</span>
        <span class="property-indicator"></span>
        <span class="property-type">int?</span>
    </dt>
    <dd>{{% md %}}The time in seconds, the instance is allowed to run while detached from the ELB. This is to allow the instance time to be drained from incoming TCP connections before terminating it, during a scale down operation.
{{% /md %}}</dd>

    <dt class="property-optional"
            title="Optional">
        <span>Ebs<wbr>Block<wbr>Devices</span>
        <span class="property-indicator"></span>
        <span class="property-type"><a href="#elastigroupebsblockdevice">List&lt;Elastigroup<wbr>Ebs<wbr>Block<wbr>Device<wbr>Args&gt;?</a></span>
    </dt>
    <dd>{{% md %}}{{% /md %}}</dd>

    <dt class="property-optional"
            title="Optional">
        <span>Ebs<wbr>Optimized</span>
        <span class="property-indicator"></span>
        <span class="property-type">bool?</span>
    </dt>
    <dd>{{% md %}}Enable high bandwidth connectivity between instances and AWS’s Elastic Block Store (EBS). For instance types that are EBS-optimized by default this parameter will be ignored.
{{% /md %}}</dd>

    <dt class="property-optional"
            title="Optional">
        <span>Elastic<wbr>Ips</span>
        <span class="property-indicator"></span>
        <span class="property-type">List<string>?</span>
    </dt>
    <dd>{{% md %}}A list of [AWS Elastic IP](http://docs.aws.amazon.com/AWSEC2/latest/UserGuide/elastic-ip-addresses-eip.html) allocation IDs to associate to the group instances.
{{% /md %}}</dd>

    <dt class="property-optional"
            title="Optional">
        <span>Elastic<wbr>Load<wbr>Balancers</span>
        <span class="property-indicator"></span>
        <span class="property-type">List<string>?</span>
    </dt>
    <dd>{{% md %}}{{% /md %}}</dd>

    <dt class="property-optional"
            title="Optional">
        <span>Enable<wbr>Monitoring</span>
        <span class="property-indicator"></span>
        <span class="property-type">bool?</span>
    </dt>
    <dd>{{% md %}}Indicates whether monitoring is enabled for the instance.
{{% /md %}}</dd>

    <dt class="property-optional"
            title="Optional">
        <span>Ephemeral<wbr>Block<wbr>Devices</span>
        <span class="property-indicator"></span>
        <span class="property-type"><a href="#elastigroupephemeralblockdevice">List&lt;Elastigroup<wbr>Ephemeral<wbr>Block<wbr>Device<wbr>Args&gt;?</a></span>
    </dt>
    <dd>{{% md %}}{{% /md %}}</dd>

    <dt class="property-required"
            title="Required">
        <span>Fallback<wbr>To<wbr>Ondemand</span>
        <span class="property-indicator"></span>
        <span class="property-type">bool</span>
    </dt>
    <dd>{{% md %}}In a case of no Spot instances available, Elastigroup will launch on-demand instances instead.
{{% /md %}}</dd>

    <dt class="property-optional"
            title="Optional">
        <span>Health<wbr>Check<wbr>Grace<wbr>Period</span>
        <span class="property-indicator"></span>
        <span class="property-type">int?</span>
    </dt>
    <dd>{{% md %}}The amount of time, in seconds, after the instance has launched to starts and check its health.
{{% /md %}}</dd>

    <dt class="property-optional"
            title="Optional">
        <span>Health<wbr>Check<wbr>Type</span>
        <span class="property-indicator"></span>
        <span class="property-type">string?</span>
    </dt>
    <dd>{{% md %}}The service that will perform health checks for the instance. Valid values: `"ELB"`, `"HCS"`, `"TARGET_GROUP"`, `"MLB"`, `"EC2"`, `"MULTAI_TARGET_SET"`, `"MLB_RUNTIME"`, `"K8S_NODE"`, `"NOMAD_NODE"`, `"ECS_CLUSTER_INSTANCE"`.
{{% /md %}}</dd>

    <dt class="property-optional"
            title="Optional">
        <span>Health<wbr>Check<wbr>Unhealthy<wbr>Duration<wbr>Before<wbr>Replacement</span>
        <span class="property-indicator"></span>
        <span class="property-type">int?</span>
    </dt>
    <dd>{{% md %}}The amount of time, in seconds, that we will wait before replacing an instance that is running and became unhealthy (this is only applicable for instances that were once healthy).
{{% /md %}}</dd>

    <dt class="property-optional"
            title="Optional">
        <span>Iam<wbr>Instance<wbr>Profile</span>
        <span class="property-indicator"></span>
        <span class="property-type">string?</span>
    </dt>
    <dd>{{% md %}}The ARN or name of an IAM instance profile to associate with launched instances.
{{% /md %}}</dd>

    <dt class="property-optional"
            title="Optional">
        <span>Image<wbr>Id</span>
        <span class="property-indicator"></span>
        <span class="property-type">string?</span>
    </dt>
    <dd>{{% md %}}The ID of the AMI used to launch the instance.
{{% /md %}}</dd>

    <dt class="property-required"
            title="Required">
        <span>Instance<wbr>Types<wbr>Ondemand</span>
        <span class="property-indicator"></span>
        <span class="property-type">string</span>
    </dt>
    <dd>{{% md %}}The type of instance determines your instance's CPU capacity, memory and storage (e.g., m1.small, c1.xlarge).
{{% /md %}}</dd>

    <dt class="property-optional"
            title="Optional">
        <span>Instance<wbr>Types<wbr>Preferred<wbr>Spots</span>
        <span class="property-indicator"></span>
        <span class="property-type">List<string>?</span>
    </dt>
    <dd>{{% md %}}Prioritize a subset of spot instance types. Must be a subset of the selected spot instance types.
{{% /md %}}</dd>

    <dt class="property-required"
            title="Required">
        <span>Instance<wbr>Types<wbr>Spots</span>
        <span class="property-indicator"></span>
        <span class="property-type">List<string></span>
    </dt>
    <dd>{{% md %}}One or more instance types.
{{% /md %}}</dd>

    <dt class="property-optional"
            title="Optional">
        <span>Instance<wbr>Types<wbr>Weights</span>
        <span class="property-indicator"></span>
        <span class="property-type"><a href="#elastigroupinstancetypesweight">List&lt;Elastigroup<wbr>Instance<wbr>Types<wbr>Weight<wbr>Args&gt;?</a></span>
    </dt>
    <dd>{{% md %}}List of weights per instance type for weighted groups. Each object in the list should have the following attributes:
{{% /md %}}</dd>

    <dt class="property-optional"
            title="Optional">
        <span>Integration<wbr>Beanstalk</span>
        <span class="property-indicator"></span>
        <span class="property-type"><a href="#elastigroupintegrationbeanstalk">Elastigroup<wbr>Integration<wbr>Beanstalk<wbr>Args?</a></span>
    </dt>
    <dd>{{% md %}}{{% /md %}}</dd>

    <dt class="property-optional"
            title="Optional">
        <span>Integration<wbr>Codedeploy</span>
        <span class="property-indicator"></span>
        <span class="property-type"><a href="#elastigroupintegrationcodedeploy">Elastigroup<wbr>Integration<wbr>Codedeploy<wbr>Args?</a></span>
    </dt>
    <dd>{{% md %}}{{% /md %}}</dd>

    <dt class="property-optional"
            title="Optional">
        <span>Integration<wbr>Docker<wbr>Swarm</span>
        <span class="property-indicator"></span>
        <span class="property-type"><a href="#elastigroupintegrationdockerswarm">Elastigroup<wbr>Integration<wbr>Docker<wbr>Swarm<wbr>Args?</a></span>
    </dt>
    <dd>{{% md %}}{{% /md %}}</dd>

    <dt class="property-optional"
            title="Optional">
        <span>Integration<wbr>Ecs</span>
        <span class="property-indicator"></span>
        <span class="property-type"><a href="#elastigroupintegrationecs">Elastigroup<wbr>Integration<wbr>Ecs<wbr>Args?</a></span>
    </dt>
    <dd>{{% md %}}{{% /md %}}</dd>

    <dt class="property-optional"
            title="Optional">
        <span>Integration<wbr>Gitlab</span>
        <span class="property-indicator"></span>
        <span class="property-type"><a href="#elastigroupintegrationgitlab">Elastigroup<wbr>Integration<wbr>Gitlab<wbr>Args?</a></span>
    </dt>
    <dd>{{% md %}}{{% /md %}}</dd>

    <dt class="property-optional"
            title="Optional">
        <span>Integration<wbr>Kubernetes</span>
        <span class="property-indicator"></span>
        <span class="property-type"><a href="#elastigroupintegrationkubernetes">Elastigroup<wbr>Integration<wbr>Kubernetes<wbr>Args?</a></span>
    </dt>
    <dd>{{% md %}}{{% /md %}}</dd>

    <dt class="property-optional"
            title="Optional">
        <span>Integration<wbr>Mesosphere</span>
        <span class="property-indicator"></span>
        <span class="property-type"><a href="#elastigroupintegrationmesosphere">Elastigroup<wbr>Integration<wbr>Mesosphere<wbr>Args?</a></span>
    </dt>
    <dd>{{% md %}}{{% /md %}}</dd>

    <dt class="property-optional"
            title="Optional">
        <span>Integration<wbr>Multai<wbr>Runtime</span>
        <span class="property-indicator"></span>
        <span class="property-type"><a href="#elastigroupintegrationmultairuntime">Elastigroup<wbr>Integration<wbr>Multai<wbr>Runtime<wbr>Args?</a></span>
    </dt>
    <dd>{{% md %}}{{% /md %}}</dd>

    <dt class="property-optional"
            title="Optional">
        <span>Integration<wbr>Nomad</span>
        <span class="property-indicator"></span>
        <span class="property-type"><a href="#elastigroupintegrationnomad">Elastigroup<wbr>Integration<wbr>Nomad<wbr>Args?</a></span>
    </dt>
    <dd>{{% md %}}{{% /md %}}</dd>

    <dt class="property-optional"
            title="Optional">
        <span>Integration<wbr>Rancher</span>
        <span class="property-indicator"></span>
        <span class="property-type"><a href="#elastigroupintegrationrancher">Elastigroup<wbr>Integration<wbr>Rancher<wbr>Args?</a></span>
    </dt>
    <dd>{{% md %}}{{% /md %}}</dd>

    <dt class="property-optional"
            title="Optional">
        <span>Integration<wbr>Route53</span>
        <span class="property-indicator"></span>
        <span class="property-type"><a href="#elastigroupintegrationroute53">Elastigroup<wbr>Integration<wbr>Route53Args?</a></span>
    </dt>
    <dd>{{% md %}}{{% /md %}}</dd>

    <dt class="property-optional"
            title="Optional">
        <span>Key<wbr>Name</span>
        <span class="property-indicator"></span>
        <span class="property-type">string?</span>
    </dt>
    <dd>{{% md %}}The key name that should be used for the instance.
{{% /md %}}</dd>

    <dt class="property-optional"
            title="Optional">
        <span>Lifetime<wbr>Period</span>
        <span class="property-indicator"></span>
        <span class="property-type">string?</span>
    </dt>
    <dd>{{% md %}}{{% /md %}}</dd>

    <dt class="property-optional"
            title="Optional">
        <span>Max<wbr>Size</span>
        <span class="property-indicator"></span>
        <span class="property-type">int?</span>
    </dt>
    <dd>{{% md %}}The maximum number of instances the group should have at any time.
{{% /md %}}</dd>

    <dt class="property-optional"
            title="Optional">
        <span>Min<wbr>Size</span>
        <span class="property-indicator"></span>
        <span class="property-type">int?</span>
    </dt>
    <dd>{{% md %}}The minimum number of instances the group should have at any time.
{{% /md %}}</dd>

    <dt class="property-optional"
            title="Optional">
        <span>Multai<wbr>Target<wbr>Sets</span>
        <span class="property-indicator"></span>
        <span class="property-type"><a href="#elastigroupmultaitargetset">List&lt;Elastigroup<wbr>Multai<wbr>Target<wbr>Set<wbr>Args&gt;?</a></span>
    </dt>
    <dd>{{% md %}}{{% /md %}}</dd>

    <dt class="property-optional"
            title="Optional">
        <span>Name</span>
        <span class="property-indicator"></span>
        <span class="property-type">string?</span>
    </dt>
    <dd>{{% md %}}The group name.
{{% /md %}}</dd>

    <dt class="property-optional"
            title="Optional">
        <span>Network<wbr>Interfaces</span>
        <span class="property-indicator"></span>
        <span class="property-type"><a href="#elastigroupnetworkinterface">List&lt;Elastigroup<wbr>Network<wbr>Interface<wbr>Args&gt;?</a></span>
    </dt>
    <dd>{{% md %}}{{% /md %}}</dd>

    <dt class="property-optional"
            title="Optional">
        <span>Ondemand<wbr>Count</span>
        <span class="property-indicator"></span>
        <span class="property-type">int?</span>
    </dt>
    <dd>{{% md %}}Number of on demand instances to launch in the group. All other instances will be spot instances. When this parameter is set the `spot_percentage` parameter is being ignored.
{{% /md %}}</dd>

    <dt class="property-required"
            title="Required">
        <span>Orientation</span>
        <span class="property-indicator"></span>
        <span class="property-type">string</span>
    </dt>
    <dd>{{% md %}}Select a prediction strategy. Valid values: `"balanced"`, `"costOriented"`, `"equalAzDistribution"`, `"availabilityOriented"`.    
{{% /md %}}</dd>

    <dt class="property-optional"
            title="Optional">
        <span>Persist<wbr>Block<wbr>Devices</span>
        <span class="property-indicator"></span>
        <span class="property-type">bool?</span>
    </dt>
    <dd>{{% md %}}{{% /md %}}</dd>

    <dt class="property-optional"
            title="Optional">
        <span>Persist<wbr>Private<wbr>Ip</span>
        <span class="property-indicator"></span>
        <span class="property-type">bool?</span>
    </dt>
    <dd>{{% md %}}{{% /md %}}</dd>

    <dt class="property-optional"
            title="Optional">
        <span>Persist<wbr>Root<wbr>Device</span>
        <span class="property-indicator"></span>
        <span class="property-type">bool?</span>
    </dt>
    <dd>{{% md %}}{{% /md %}}</dd>

    <dt class="property-optional"
            title="Optional">
        <span>Placement<wbr>Tenancy</span>
        <span class="property-indicator"></span>
        <span class="property-type">string?</span>
    </dt>
    <dd>{{% md %}}Enable dedicated tenancy. Note: There is a flat hourly fee for each region in which dedicated tenancy is used.
{{% /md %}}</dd>

    <dt class="property-optional"
            title="Optional">
        <span>Preferred<wbr>Availability<wbr>Zones</span>
        <span class="property-indicator"></span>
        <span class="property-type">List<string>?</span>
    </dt>
    <dd>{{% md %}}The AZs to prioritize when launching Spot instances. If no markets are available in the Preferred AZs, Spot instances are launched in the non-preferred AZs. 
Note: Must be a sublist of `availability_zones` and `orientation` value must not be `"equalAzDistribution"`.
{{% /md %}}</dd>

    <dt class="property-optional"
            title="Optional">
        <span>Private<wbr>Ips</span>
        <span class="property-indicator"></span>
        <span class="property-type">List<string>?</span>
    </dt>
    <dd>{{% md %}}{{% /md %}}</dd>

    <dt class="property-required"
            title="Required">
        <span>Product</span>
        <span class="property-indicator"></span>
        <span class="property-type">string</span>
    </dt>
    <dd>{{% md %}}Operation system type. Valid values: `"Linux/UNIX"`, `"SUSE Linux"`, `"Windows"`. 
For EC2 Classic instances:  `"Linux/UNIX (Amazon VPC)"`, `"SUSE Linux (Amazon VPC)"`, `"Windows (Amazon VPC)"`.
{{% /md %}}</dd>

    <dt class="property-optional"
            title="Optional">
        <span>Region</span>
        <span class="property-indicator"></span>
        <span class="property-type">string?</span>
    </dt>
    <dd>{{% md %}}The AWS region your group will be created in.
Note: This parameter is required if you specify subnets (through subnet_ids). This parameter is optional if you specify Availability Zones (through availability_zones).
{{% /md %}}</dd>

    <dt class="property-optional"
            title="Optional">
        <span>Revert<wbr>To<wbr>Spot</span>
        <span class="property-indicator"></span>
        <span class="property-type"><a href="#elastigroupreverttospot">Elastigroup<wbr>Revert<wbr>To<wbr>Spot<wbr>Args?</a></span>
    </dt>
    <dd>{{% md %}}Hold settings for strategy correction – replacing On-Demand for Spot instances. Supported Values: `"never"`, `"always"`, `"timeWindow"`
{{% /md %}}</dd>

    <dt class="property-optional"
            title="Optional">
        <span>Scaling<wbr>Down<wbr>Policies</span>
        <span class="property-indicator"></span>
        <span class="property-type"><a href="#elastigroupscalingdownpolicy">List&lt;Elastigroup<wbr>Scaling<wbr>Down<wbr>Policy<wbr>Args&gt;?</a></span>
    </dt>
    <dd>{{% md %}}{{% /md %}}</dd>

    <dt class="property-optional"
            title="Optional">
        <span>Scaling<wbr>Strategies</span>
        <span class="property-indicator"></span>
        <span class="property-type"><a href="#elastigroupscalingstrategy">List&lt;Elastigroup<wbr>Scaling<wbr>Strategy<wbr>Args&gt;?</a></span>
    </dt>
    <dd>{{% md %}}Set termination policy.
{{% /md %}}</dd>

    <dt class="property-optional"
            title="Optional">
        <span>Scaling<wbr>Target<wbr>Policies</span>
        <span class="property-indicator"></span>
        <span class="property-type"><a href="#elastigroupscalingtargetpolicy">List&lt;Elastigroup<wbr>Scaling<wbr>Target<wbr>Policy<wbr>Args&gt;?</a></span>
    </dt>
    <dd>{{% md %}}{{% /md %}}</dd>

    <dt class="property-optional"
            title="Optional">
        <span>Scaling<wbr>Up<wbr>Policies</span>
        <span class="property-indicator"></span>
        <span class="property-type"><a href="#elastigroupscalinguppolicy">List&lt;Elastigroup<wbr>Scaling<wbr>Up<wbr>Policy<wbr>Args&gt;?</a></span>
    </dt>
    <dd>{{% md %}}{{% /md %}}</dd>

    <dt class="property-optional"
            title="Optional">
        <span>Scheduled<wbr>Tasks</span>
        <span class="property-indicator"></span>
        <span class="property-type"><a href="#elastigroupscheduledtask">List&lt;Elastigroup<wbr>Scheduled<wbr>Task<wbr>Args&gt;?</a></span>
    </dt>
    <dd>{{% md %}}{{% /md %}}</dd>

    <dt class="property-required"
            title="Required">
        <span>Security<wbr>Groups</span>
        <span class="property-indicator"></span>
        <span class="property-type">List<string></span>
    </dt>
    <dd>{{% md %}}A list of associated security group IDS.
{{% /md %}}</dd>

    <dt class="property-optional"
            title="Optional">
        <span>Shutdown<wbr>Script</span>
        <span class="property-indicator"></span>
        <span class="property-type">string?</span>
    </dt>
    <dd>{{% md %}}The Base64-encoded shutdown script that executes prior to instance termination, for more information please see: [Shutdown Script](https://api.spotinst.com/integration-docs/elastigroup/concepts/compute-concepts/shutdown-scripts/)
{{% /md %}}</dd>

    <dt class="property-optional"
            title="Optional">
        <span>Signals</span>
        <span class="property-indicator"></span>
        <span class="property-type"><a href="#elastigroupsignal">List&lt;Elastigroup<wbr>Signal<wbr>Args&gt;?</a></span>
    </dt>
    <dd>{{% md %}}{{% /md %}}</dd>

    <dt class="property-optional"
            title="Optional">
        <span>Spot<wbr>Percentage</span>
        <span class="property-indicator"></span>
        <span class="property-type">double?</span>
    </dt>
    <dd>{{% md %}}The percentage of Spot instances that would spin up from the `desired_capacity` number.
{{% /md %}}</dd>

    <dt class="property-optional"
            title="Optional">
        <span>Stateful<wbr>Deallocation</span>
        <span class="property-indicator"></span>
        <span class="property-type"><a href="#elastigroupstatefuldeallocation">Elastigroup<wbr>Stateful<wbr>Deallocation<wbr>Args?</a></span>
    </dt>
    <dd>{{% md %}}{{% /md %}}</dd>

    <dt class="property-optional"
            title="Optional">
        <span>Subnet<wbr>Ids</span>
        <span class="property-indicator"></span>
        <span class="property-type">List<string>?</span>
    </dt>
    <dd>{{% md %}}List of Strings of subnet identifiers.
Note: When this parameter is set, `availability_zones` should be left unused.
{{% /md %}}</dd>

    <dt class="property-optional"
            title="Optional">
        <span>Tags</span>
        <span class="property-indicator"></span>
        <span class="property-type"><a href="#elastigrouptag">List&lt;Elastigroup<wbr>Tag<wbr>Args&gt;?</a></span>
    </dt>
    <dd>{{% md %}}A key/value mapping of tags to assign to the resource.
{{% /md %}}</dd>

    <dt class="property-optional"
            title="Optional">
        <span>Target<wbr>Group<wbr>Arns</span>
        <span class="property-indicator"></span>
        <span class="property-type">List<string>?</span>
    </dt>
    <dd>{{% md %}}{{% /md %}}</dd>

    <dt class="property-optional"
            title="Optional">
        <span>Update<wbr>Policy</span>
        <span class="property-indicator"></span>
        <span class="property-type"><a href="#elastigroupupdatepolicy">Elastigroup<wbr>Update<wbr>Policy<wbr>Args?</a></span>
    </dt>
    <dd>{{% md %}}{{% /md %}}</dd>

    <dt class="property-optional"
            title="Optional">
        <span>User<wbr>Data</span>
        <span class="property-indicator"></span>
        <span class="property-type">string?</span>
    </dt>
    <dd>{{% md %}}The user data to provide when launching the instance.
{{% /md %}}</dd>

    <dt class="property-optional"
            title="Optional">
        <span>Utilize<wbr>Reserved<wbr>Instances</span>
        <span class="property-indicator"></span>
        <span class="property-type">bool?</span>
    </dt>
    <dd>{{% md %}}In a case of any available reserved instances, Elastigroup will utilize them first before purchasing Spot instances.
{{% /md %}}</dd>

    <dt class="property-optional"
            title="Optional">
        <span>Wait<wbr>For<wbr>Capacity</span>
        <span class="property-indicator"></span>
        <span class="property-type">int?</span>
    </dt>
    <dd>{{% md %}}Minimum number of instances in a 'HEALTHY' status that is required before continuing. This is ignored when updating with blue/green deployment. Cannot exceed `desired_capacity`.
{{% /md %}}</dd>

    <dt class="property-optional"
            title="Optional">
        <span>Wait<wbr>For<wbr>Capacity<wbr>Timeout</span>
        <span class="property-indicator"></span>
        <span class="property-type">int?</span>
    </dt>
    <dd>{{% md %}}Time (seconds) to wait for instances to report a 'HEALTHY' status. Useful for plans with multiple dependencies that take some time to initialize. Leave undefined or set to `0` to indicate no wait. This is ignored when updating with blue/green deployment. 
{{% /md %}}</dd>

</dl>
{{% /choosable %}}


{{% choosable language go %}}
<dl class="resources-properties">

    <dt class="property-optional"
            title="Optional">
        <span>Availability<wbr>Zones</span>
        <span class="property-indicator"></span>
        <span class="property-type">[]string</span>
    </dt>
    <dd>{{% md %}}List of Strings of availability zones. When this parameter is set, `subnet_ids` should be left unused.
Note: `availability_zones` naming syntax follows the convention `availability-zone:subnet:placement-group-name`. For example, to set an AZ in `us-east-1` with subnet `subnet-123456` and placement group `ClusterI03`, you would set:
`availability_zones = ["us-east-1a:subnet-123456:ClusterI03"]`
{{% /md %}}</dd>

    <dt class="property-optional"
            title="Optional">
        <span>Block<wbr>Devices<wbr>Mode</span>
        <span class="property-indicator"></span>
        <span class="property-type">*string</span>
    </dt>
    <dd>{{% md %}}{{% /md %}}</dd>

    <dt class="property-optional"
            title="Optional">
        <span>Capacity<wbr>Unit</span>
        <span class="property-indicator"></span>
        <span class="property-type">*string</span>
    </dt>
    <dd>{{% md %}}The capacity unit to launch instances by. If not specified, when choosing the weight unit, each instance will weight as the number of its vCPUs.
{{% /md %}}</dd>

    <dt class="property-optional"
            title="Optional">
        <span>Cpu<wbr>Credits</span>
        <span class="property-indicator"></span>
        <span class="property-type">*string</span>
    </dt>
    <dd>{{% md %}}Controls how T3 instances are launched. Valid values: `standard`, `unlimited`.
{{% /md %}}</dd>

    <dt class="property-optional"
            title="Optional">
        <span>Description</span>
        <span class="property-indicator"></span>
        <span class="property-type">*string</span>
    </dt>
    <dd>{{% md %}}The group description.
{{% /md %}}</dd>

    <dt class="property-optional"
            title="Optional">
        <span>Desired<wbr>Capacity</span>
        <span class="property-indicator"></span>
        <span class="property-type">*int</span>
    </dt>
    <dd>{{% md %}}The desired number of instances the group should have at any time.
{{% /md %}}</dd>

    <dt class="property-optional"
            title="Optional">
        <span>Draining<wbr>Timeout</span>
        <span class="property-indicator"></span>
        <span class="property-type">*int</span>
    </dt>
    <dd>{{% md %}}The time in seconds, the instance is allowed to run while detached from the ELB. This is to allow the instance time to be drained from incoming TCP connections before terminating it, during a scale down operation.
{{% /md %}}</dd>

    <dt class="property-optional"
            title="Optional">
        <span>Ebs<wbr>Block<wbr>Devices</span>
        <span class="property-indicator"></span>
        <span class="property-type"><a href="#elastigroupebsblockdevice">[]Elastigroup<wbr>Ebs<wbr>Block<wbr>Device</a></span>
    </dt>
    <dd>{{% md %}}{{% /md %}}</dd>

    <dt class="property-optional"
            title="Optional">
        <span>Ebs<wbr>Optimized</span>
        <span class="property-indicator"></span>
        <span class="property-type">*bool</span>
    </dt>
    <dd>{{% md %}}Enable high bandwidth connectivity between instances and AWS’s Elastic Block Store (EBS). For instance types that are EBS-optimized by default this parameter will be ignored.
{{% /md %}}</dd>

    <dt class="property-optional"
            title="Optional">
        <span>Elastic<wbr>Ips</span>
        <span class="property-indicator"></span>
        <span class="property-type">[]string</span>
    </dt>
    <dd>{{% md %}}A list of [AWS Elastic IP](http://docs.aws.amazon.com/AWSEC2/latest/UserGuide/elastic-ip-addresses-eip.html) allocation IDs to associate to the group instances.
{{% /md %}}</dd>

    <dt class="property-optional"
            title="Optional">
        <span>Elastic<wbr>Load<wbr>Balancers</span>
        <span class="property-indicator"></span>
        <span class="property-type">[]string</span>
    </dt>
    <dd>{{% md %}}{{% /md %}}</dd>

    <dt class="property-optional"
            title="Optional">
        <span>Enable<wbr>Monitoring</span>
        <span class="property-indicator"></span>
        <span class="property-type">*bool</span>
    </dt>
    <dd>{{% md %}}Indicates whether monitoring is enabled for the instance.
{{% /md %}}</dd>

    <dt class="property-optional"
            title="Optional">
        <span>Ephemeral<wbr>Block<wbr>Devices</span>
        <span class="property-indicator"></span>
        <span class="property-type"><a href="#elastigroupephemeralblockdevice">[]Elastigroup<wbr>Ephemeral<wbr>Block<wbr>Device</a></span>
    </dt>
    <dd>{{% md %}}{{% /md %}}</dd>

    <dt class="property-required"
            title="Required">
        <span>Fallback<wbr>To<wbr>Ondemand</span>
        <span class="property-indicator"></span>
        <span class="property-type">bool</span>
    </dt>
    <dd>{{% md %}}In a case of no Spot instances available, Elastigroup will launch on-demand instances instead.
{{% /md %}}</dd>

    <dt class="property-optional"
            title="Optional">
        <span>Health<wbr>Check<wbr>Grace<wbr>Period</span>
        <span class="property-indicator"></span>
        <span class="property-type">*int</span>
    </dt>
    <dd>{{% md %}}The amount of time, in seconds, after the instance has launched to starts and check its health.
{{% /md %}}</dd>

    <dt class="property-optional"
            title="Optional">
        <span>Health<wbr>Check<wbr>Type</span>
        <span class="property-indicator"></span>
        <span class="property-type">*string</span>
    </dt>
    <dd>{{% md %}}The service that will perform health checks for the instance. Valid values: `"ELB"`, `"HCS"`, `"TARGET_GROUP"`, `"MLB"`, `"EC2"`, `"MULTAI_TARGET_SET"`, `"MLB_RUNTIME"`, `"K8S_NODE"`, `"NOMAD_NODE"`, `"ECS_CLUSTER_INSTANCE"`.
{{% /md %}}</dd>

    <dt class="property-optional"
            title="Optional">
        <span>Health<wbr>Check<wbr>Unhealthy<wbr>Duration<wbr>Before<wbr>Replacement</span>
        <span class="property-indicator"></span>
        <span class="property-type">*int</span>
    </dt>
    <dd>{{% md %}}The amount of time, in seconds, that we will wait before replacing an instance that is running and became unhealthy (this is only applicable for instances that were once healthy).
{{% /md %}}</dd>

    <dt class="property-optional"
            title="Optional">
        <span>Iam<wbr>Instance<wbr>Profile</span>
        <span class="property-indicator"></span>
        <span class="property-type">*string</span>
    </dt>
    <dd>{{% md %}}The ARN or name of an IAM instance profile to associate with launched instances.
{{% /md %}}</dd>

    <dt class="property-optional"
            title="Optional">
        <span>Image<wbr>Id</span>
        <span class="property-indicator"></span>
        <span class="property-type">*string</span>
    </dt>
    <dd>{{% md %}}The ID of the AMI used to launch the instance.
{{% /md %}}</dd>

    <dt class="property-required"
            title="Required">
        <span>Instance<wbr>Types<wbr>Ondemand</span>
        <span class="property-indicator"></span>
        <span class="property-type">string</span>
    </dt>
    <dd>{{% md %}}The type of instance determines your instance's CPU capacity, memory and storage (e.g., m1.small, c1.xlarge).
{{% /md %}}</dd>

    <dt class="property-optional"
            title="Optional">
        <span>Instance<wbr>Types<wbr>Preferred<wbr>Spots</span>
        <span class="property-indicator"></span>
        <span class="property-type">[]string</span>
    </dt>
    <dd>{{% md %}}Prioritize a subset of spot instance types. Must be a subset of the selected spot instance types.
{{% /md %}}</dd>

    <dt class="property-required"
            title="Required">
        <span>Instance<wbr>Types<wbr>Spots</span>
        <span class="property-indicator"></span>
        <span class="property-type">[]string</span>
    </dt>
    <dd>{{% md %}}One or more instance types.
{{% /md %}}</dd>

    <dt class="property-optional"
            title="Optional">
        <span>Instance<wbr>Types<wbr>Weights</span>
        <span class="property-indicator"></span>
        <span class="property-type"><a href="#elastigroupinstancetypesweight">[]Elastigroup<wbr>Instance<wbr>Types<wbr>Weight</a></span>
    </dt>
    <dd>{{% md %}}List of weights per instance type for weighted groups. Each object in the list should have the following attributes:
{{% /md %}}</dd>

    <dt class="property-optional"
            title="Optional">
        <span>Integration<wbr>Beanstalk</span>
        <span class="property-indicator"></span>
        <span class="property-type"><a href="#elastigroupintegrationbeanstalk">*Elastigroup<wbr>Integration<wbr>Beanstalk</a></span>
    </dt>
    <dd>{{% md %}}{{% /md %}}</dd>

    <dt class="property-optional"
            title="Optional">
        <span>Integration<wbr>Codedeploy</span>
        <span class="property-indicator"></span>
        <span class="property-type"><a href="#elastigroupintegrationcodedeploy">*Elastigroup<wbr>Integration<wbr>Codedeploy</a></span>
    </dt>
    <dd>{{% md %}}{{% /md %}}</dd>

    <dt class="property-optional"
            title="Optional">
        <span>Integration<wbr>Docker<wbr>Swarm</span>
        <span class="property-indicator"></span>
        <span class="property-type"><a href="#elastigroupintegrationdockerswarm">*Elastigroup<wbr>Integration<wbr>Docker<wbr>Swarm</a></span>
    </dt>
    <dd>{{% md %}}{{% /md %}}</dd>

    <dt class="property-optional"
            title="Optional">
        <span>Integration<wbr>Ecs</span>
        <span class="property-indicator"></span>
        <span class="property-type"><a href="#elastigroupintegrationecs">*Elastigroup<wbr>Integration<wbr>Ecs</a></span>
    </dt>
    <dd>{{% md %}}{{% /md %}}</dd>

    <dt class="property-optional"
            title="Optional">
        <span>Integration<wbr>Gitlab</span>
        <span class="property-indicator"></span>
        <span class="property-type"><a href="#elastigroupintegrationgitlab">*Elastigroup<wbr>Integration<wbr>Gitlab</a></span>
    </dt>
    <dd>{{% md %}}{{% /md %}}</dd>

    <dt class="property-optional"
            title="Optional">
        <span>Integration<wbr>Kubernetes</span>
        <span class="property-indicator"></span>
        <span class="property-type"><a href="#elastigroupintegrationkubernetes">*Elastigroup<wbr>Integration<wbr>Kubernetes</a></span>
    </dt>
    <dd>{{% md %}}{{% /md %}}</dd>

    <dt class="property-optional"
            title="Optional">
        <span>Integration<wbr>Mesosphere</span>
        <span class="property-indicator"></span>
        <span class="property-type"><a href="#elastigroupintegrationmesosphere">*Elastigroup<wbr>Integration<wbr>Mesosphere</a></span>
    </dt>
    <dd>{{% md %}}{{% /md %}}</dd>

    <dt class="property-optional"
            title="Optional">
        <span>Integration<wbr>Multai<wbr>Runtime</span>
        <span class="property-indicator"></span>
        <span class="property-type"><a href="#elastigroupintegrationmultairuntime">*Elastigroup<wbr>Integration<wbr>Multai<wbr>Runtime</a></span>
    </dt>
    <dd>{{% md %}}{{% /md %}}</dd>

    <dt class="property-optional"
            title="Optional">
        <span>Integration<wbr>Nomad</span>
        <span class="property-indicator"></span>
        <span class="property-type"><a href="#elastigroupintegrationnomad">*Elastigroup<wbr>Integration<wbr>Nomad</a></span>
    </dt>
    <dd>{{% md %}}{{% /md %}}</dd>

    <dt class="property-optional"
            title="Optional">
        <span>Integration<wbr>Rancher</span>
        <span class="property-indicator"></span>
        <span class="property-type"><a href="#elastigroupintegrationrancher">*Elastigroup<wbr>Integration<wbr>Rancher</a></span>
    </dt>
    <dd>{{% md %}}{{% /md %}}</dd>

    <dt class="property-optional"
            title="Optional">
        <span>Integration<wbr>Route53</span>
        <span class="property-indicator"></span>
        <span class="property-type"><a href="#elastigroupintegrationroute53">*Elastigroup<wbr>Integration<wbr>Route53</a></span>
    </dt>
    <dd>{{% md %}}{{% /md %}}</dd>

    <dt class="property-optional"
            title="Optional">
        <span>Key<wbr>Name</span>
        <span class="property-indicator"></span>
        <span class="property-type">*string</span>
    </dt>
    <dd>{{% md %}}The key name that should be used for the instance.
{{% /md %}}</dd>

    <dt class="property-optional"
            title="Optional">
        <span>Lifetime<wbr>Period</span>
        <span class="property-indicator"></span>
        <span class="property-type">*string</span>
    </dt>
    <dd>{{% md %}}{{% /md %}}</dd>

    <dt class="property-optional"
            title="Optional">
        <span>Max<wbr>Size</span>
        <span class="property-indicator"></span>
        <span class="property-type">*int</span>
    </dt>
    <dd>{{% md %}}The maximum number of instances the group should have at any time.
{{% /md %}}</dd>

    <dt class="property-optional"
            title="Optional">
        <span>Min<wbr>Size</span>
        <span class="property-indicator"></span>
        <span class="property-type">*int</span>
    </dt>
    <dd>{{% md %}}The minimum number of instances the group should have at any time.
{{% /md %}}</dd>

    <dt class="property-optional"
            title="Optional">
        <span>Multai<wbr>Target<wbr>Sets</span>
        <span class="property-indicator"></span>
        <span class="property-type"><a href="#elastigroupmultaitargetset">[]Elastigroup<wbr>Multai<wbr>Target<wbr>Set</a></span>
    </dt>
    <dd>{{% md %}}{{% /md %}}</dd>

    <dt class="property-optional"
            title="Optional">
        <span>Name</span>
        <span class="property-indicator"></span>
        <span class="property-type">*string</span>
    </dt>
    <dd>{{% md %}}The group name.
{{% /md %}}</dd>

    <dt class="property-optional"
            title="Optional">
        <span>Network<wbr>Interfaces</span>
        <span class="property-indicator"></span>
        <span class="property-type"><a href="#elastigroupnetworkinterface">[]Elastigroup<wbr>Network<wbr>Interface</a></span>
    </dt>
    <dd>{{% md %}}{{% /md %}}</dd>

    <dt class="property-optional"
            title="Optional">
        <span>Ondemand<wbr>Count</span>
        <span class="property-indicator"></span>
        <span class="property-type">*int</span>
    </dt>
    <dd>{{% md %}}Number of on demand instances to launch in the group. All other instances will be spot instances. When this parameter is set the `spot_percentage` parameter is being ignored.
{{% /md %}}</dd>

    <dt class="property-required"
            title="Required">
        <span>Orientation</span>
        <span class="property-indicator"></span>
        <span class="property-type">string</span>
    </dt>
    <dd>{{% md %}}Select a prediction strategy. Valid values: `"balanced"`, `"costOriented"`, `"equalAzDistribution"`, `"availabilityOriented"`.    
{{% /md %}}</dd>

    <dt class="property-optional"
            title="Optional">
        <span>Persist<wbr>Block<wbr>Devices</span>
        <span class="property-indicator"></span>
        <span class="property-type">*bool</span>
    </dt>
    <dd>{{% md %}}{{% /md %}}</dd>

    <dt class="property-optional"
            title="Optional">
        <span>Persist<wbr>Private<wbr>Ip</span>
        <span class="property-indicator"></span>
        <span class="property-type">*bool</span>
    </dt>
    <dd>{{% md %}}{{% /md %}}</dd>

    <dt class="property-optional"
            title="Optional">
        <span>Persist<wbr>Root<wbr>Device</span>
        <span class="property-indicator"></span>
        <span class="property-type">*bool</span>
    </dt>
    <dd>{{% md %}}{{% /md %}}</dd>

    <dt class="property-optional"
            title="Optional">
        <span>Placement<wbr>Tenancy</span>
        <span class="property-indicator"></span>
        <span class="property-type">*string</span>
    </dt>
    <dd>{{% md %}}Enable dedicated tenancy. Note: There is a flat hourly fee for each region in which dedicated tenancy is used.
{{% /md %}}</dd>

    <dt class="property-optional"
            title="Optional">
        <span>Preferred<wbr>Availability<wbr>Zones</span>
        <span class="property-indicator"></span>
        <span class="property-type">[]string</span>
    </dt>
    <dd>{{% md %}}The AZs to prioritize when launching Spot instances. If no markets are available in the Preferred AZs, Spot instances are launched in the non-preferred AZs. 
Note: Must be a sublist of `availability_zones` and `orientation` value must not be `"equalAzDistribution"`.
{{% /md %}}</dd>

    <dt class="property-optional"
            title="Optional">
        <span>Private<wbr>Ips</span>
        <span class="property-indicator"></span>
        <span class="property-type">[]string</span>
    </dt>
    <dd>{{% md %}}{{% /md %}}</dd>

    <dt class="property-required"
            title="Required">
        <span>Product</span>
        <span class="property-indicator"></span>
        <span class="property-type">string</span>
    </dt>
    <dd>{{% md %}}Operation system type. Valid values: `"Linux/UNIX"`, `"SUSE Linux"`, `"Windows"`. 
For EC2 Classic instances:  `"Linux/UNIX (Amazon VPC)"`, `"SUSE Linux (Amazon VPC)"`, `"Windows (Amazon VPC)"`.
{{% /md %}}</dd>

    <dt class="property-optional"
            title="Optional">
        <span>Region</span>
        <span class="property-indicator"></span>
        <span class="property-type">*string</span>
    </dt>
    <dd>{{% md %}}The AWS region your group will be created in.
Note: This parameter is required if you specify subnets (through subnet_ids). This parameter is optional if you specify Availability Zones (through availability_zones).
{{% /md %}}</dd>

    <dt class="property-optional"
            title="Optional">
        <span>Revert<wbr>To<wbr>Spot</span>
        <span class="property-indicator"></span>
        <span class="property-type"><a href="#elastigroupreverttospot">*Elastigroup<wbr>Revert<wbr>To<wbr>Spot</a></span>
    </dt>
    <dd>{{% md %}}Hold settings for strategy correction – replacing On-Demand for Spot instances. Supported Values: `"never"`, `"always"`, `"timeWindow"`
{{% /md %}}</dd>

    <dt class="property-optional"
            title="Optional">
        <span>Scaling<wbr>Down<wbr>Policies</span>
        <span class="property-indicator"></span>
        <span class="property-type"><a href="#elastigroupscalingdownpolicy">[]Elastigroup<wbr>Scaling<wbr>Down<wbr>Policy</a></span>
    </dt>
    <dd>{{% md %}}{{% /md %}}</dd>

    <dt class="property-optional"
            title="Optional">
        <span>Scaling<wbr>Strategies</span>
        <span class="property-indicator"></span>
        <span class="property-type"><a href="#elastigroupscalingstrategy">[]Elastigroup<wbr>Scaling<wbr>Strategy</a></span>
    </dt>
    <dd>{{% md %}}Set termination policy.
{{% /md %}}</dd>

    <dt class="property-optional"
            title="Optional">
        <span>Scaling<wbr>Target<wbr>Policies</span>
        <span class="property-indicator"></span>
        <span class="property-type"><a href="#elastigroupscalingtargetpolicy">[]Elastigroup<wbr>Scaling<wbr>Target<wbr>Policy</a></span>
    </dt>
    <dd>{{% md %}}{{% /md %}}</dd>

    <dt class="property-optional"
            title="Optional">
        <span>Scaling<wbr>Up<wbr>Policies</span>
        <span class="property-indicator"></span>
        <span class="property-type"><a href="#elastigroupscalinguppolicy">[]Elastigroup<wbr>Scaling<wbr>Up<wbr>Policy</a></span>
    </dt>
    <dd>{{% md %}}{{% /md %}}</dd>

    <dt class="property-optional"
            title="Optional">
        <span>Scheduled<wbr>Tasks</span>
        <span class="property-indicator"></span>
        <span class="property-type"><a href="#elastigroupscheduledtask">[]Elastigroup<wbr>Scheduled<wbr>Task</a></span>
    </dt>
    <dd>{{% md %}}{{% /md %}}</dd>

    <dt class="property-required"
            title="Required">
        <span>Security<wbr>Groups</span>
        <span class="property-indicator"></span>
        <span class="property-type">[]string</span>
    </dt>
    <dd>{{% md %}}A list of associated security group IDS.
{{% /md %}}</dd>

    <dt class="property-optional"
            title="Optional">
        <span>Shutdown<wbr>Script</span>
        <span class="property-indicator"></span>
        <span class="property-type">*string</span>
    </dt>
    <dd>{{% md %}}The Base64-encoded shutdown script that executes prior to instance termination, for more information please see: [Shutdown Script](https://api.spotinst.com/integration-docs/elastigroup/concepts/compute-concepts/shutdown-scripts/)
{{% /md %}}</dd>

    <dt class="property-optional"
            title="Optional">
        <span>Signals</span>
        <span class="property-indicator"></span>
        <span class="property-type"><a href="#elastigroupsignal">[]Elastigroup<wbr>Signal</a></span>
    </dt>
    <dd>{{% md %}}{{% /md %}}</dd>

    <dt class="property-optional"
            title="Optional">
        <span>Spot<wbr>Percentage</span>
        <span class="property-indicator"></span>
        <span class="property-type">*float64</span>
    </dt>
    <dd>{{% md %}}The percentage of Spot instances that would spin up from the `desired_capacity` number.
{{% /md %}}</dd>

    <dt class="property-optional"
            title="Optional">
        <span>Stateful<wbr>Deallocation</span>
        <span class="property-indicator"></span>
        <span class="property-type"><a href="#elastigroupstatefuldeallocation">*Elastigroup<wbr>Stateful<wbr>Deallocation</a></span>
    </dt>
    <dd>{{% md %}}{{% /md %}}</dd>

    <dt class="property-optional"
            title="Optional">
        <span>Subnet<wbr>Ids</span>
        <span class="property-indicator"></span>
        <span class="property-type">[]string</span>
    </dt>
    <dd>{{% md %}}List of Strings of subnet identifiers.
Note: When this parameter is set, `availability_zones` should be left unused.
{{% /md %}}</dd>

    <dt class="property-optional"
            title="Optional">
        <span>Tags</span>
        <span class="property-indicator"></span>
        <span class="property-type"><a href="#elastigrouptag">[]Elastigroup<wbr>Tag</a></span>
    </dt>
    <dd>{{% md %}}A key/value mapping of tags to assign to the resource.
{{% /md %}}</dd>

    <dt class="property-optional"
            title="Optional">
        <span>Target<wbr>Group<wbr>Arns</span>
        <span class="property-indicator"></span>
        <span class="property-type">[]string</span>
    </dt>
    <dd>{{% md %}}{{% /md %}}</dd>

    <dt class="property-optional"
            title="Optional">
        <span>Update<wbr>Policy</span>
        <span class="property-indicator"></span>
        <span class="property-type"><a href="#elastigroupupdatepolicy">*Elastigroup<wbr>Update<wbr>Policy</a></span>
    </dt>
    <dd>{{% md %}}{{% /md %}}</dd>

    <dt class="property-optional"
            title="Optional">
        <span>User<wbr>Data</span>
        <span class="property-indicator"></span>
        <span class="property-type">*string</span>
    </dt>
    <dd>{{% md %}}The user data to provide when launching the instance.
{{% /md %}}</dd>

    <dt class="property-optional"
            title="Optional">
        <span>Utilize<wbr>Reserved<wbr>Instances</span>
        <span class="property-indicator"></span>
        <span class="property-type">*bool</span>
    </dt>
    <dd>{{% md %}}In a case of any available reserved instances, Elastigroup will utilize them first before purchasing Spot instances.
{{% /md %}}</dd>

    <dt class="property-optional"
            title="Optional">
        <span>Wait<wbr>For<wbr>Capacity</span>
        <span class="property-indicator"></span>
        <span class="property-type">*int</span>
    </dt>
    <dd>{{% md %}}Minimum number of instances in a 'HEALTHY' status that is required before continuing. This is ignored when updating with blue/green deployment. Cannot exceed `desired_capacity`.
{{% /md %}}</dd>

    <dt class="property-optional"
            title="Optional">
        <span>Wait<wbr>For<wbr>Capacity<wbr>Timeout</span>
        <span class="property-indicator"></span>
        <span class="property-type">*int</span>
    </dt>
    <dd>{{% md %}}Time (seconds) to wait for instances to report a 'HEALTHY' status. Useful for plans with multiple dependencies that take some time to initialize. Leave undefined or set to `0` to indicate no wait. This is ignored when updating with blue/green deployment. 
{{% /md %}}</dd>

</dl>
{{% /choosable %}}


{{% choosable language nodejs %}}
<dl class="resources-properties">

    <dt class="property-optional"
            title="Optional">
        <span>availability<wbr>Zones</span>
        <span class="property-indicator"></span>
        <span class="property-type">string[]?</span>
    </dt>
    <dd>{{% md %}}List of Strings of availability zones. When this parameter is set, `subnet_ids` should be left unused.
Note: `availability_zones` naming syntax follows the convention `availability-zone:subnet:placement-group-name`. For example, to set an AZ in `us-east-1` with subnet `subnet-123456` and placement group `ClusterI03`, you would set:
`availability_zones = ["us-east-1a:subnet-123456:ClusterI03"]`
{{% /md %}}</dd>

    <dt class="property-optional"
            title="Optional">
        <span>block<wbr>Devices<wbr>Mode</span>
        <span class="property-indicator"></span>
        <span class="property-type">string?</span>
    </dt>
    <dd>{{% md %}}{{% /md %}}</dd>

    <dt class="property-optional"
            title="Optional">
        <span>capacity<wbr>Unit</span>
        <span class="property-indicator"></span>
        <span class="property-type">string?</span>
    </dt>
    <dd>{{% md %}}The capacity unit to launch instances by. If not specified, when choosing the weight unit, each instance will weight as the number of its vCPUs.
{{% /md %}}</dd>

    <dt class="property-optional"
            title="Optional">
        <span>cpu<wbr>Credits</span>
        <span class="property-indicator"></span>
        <span class="property-type">string?</span>
    </dt>
    <dd>{{% md %}}Controls how T3 instances are launched. Valid values: `standard`, `unlimited`.
{{% /md %}}</dd>

    <dt class="property-optional"
            title="Optional">
        <span>description</span>
        <span class="property-indicator"></span>
        <span class="property-type">string?</span>
    </dt>
    <dd>{{% md %}}The group description.
{{% /md %}}</dd>

    <dt class="property-optional"
            title="Optional">
        <span>desired<wbr>Capacity</span>
        <span class="property-indicator"></span>
        <span class="property-type">number?</span>
    </dt>
    <dd>{{% md %}}The desired number of instances the group should have at any time.
{{% /md %}}</dd>

    <dt class="property-optional"
            title="Optional">
        <span>draining<wbr>Timeout</span>
        <span class="property-indicator"></span>
        <span class="property-type">number?</span>
    </dt>
    <dd>{{% md %}}The time in seconds, the instance is allowed to run while detached from the ELB. This is to allow the instance time to be drained from incoming TCP connections before terminating it, during a scale down operation.
{{% /md %}}</dd>

    <dt class="property-optional"
            title="Optional">
        <span>ebs<wbr>Block<wbr>Devices</span>
        <span class="property-indicator"></span>
        <span class="property-type"><a href="#elastigroupebsblockdevice">Elastigroup<wbr>Ebs<wbr>Block<wbr>Device[]?</a></span>
    </dt>
    <dd>{{% md %}}{{% /md %}}</dd>

    <dt class="property-optional"
            title="Optional">
        <span>ebs<wbr>Optimized</span>
        <span class="property-indicator"></span>
        <span class="property-type">boolean?</span>
    </dt>
    <dd>{{% md %}}Enable high bandwidth connectivity between instances and AWS’s Elastic Block Store (EBS). For instance types that are EBS-optimized by default this parameter will be ignored.
{{% /md %}}</dd>

    <dt class="property-optional"
            title="Optional">
        <span>elastic<wbr>Ips</span>
        <span class="property-indicator"></span>
        <span class="property-type">string[]?</span>
    </dt>
    <dd>{{% md %}}A list of [AWS Elastic IP](http://docs.aws.amazon.com/AWSEC2/latest/UserGuide/elastic-ip-addresses-eip.html) allocation IDs to associate to the group instances.
{{% /md %}}</dd>

    <dt class="property-optional"
            title="Optional">
        <span>elastic<wbr>Load<wbr>Balancers</span>
        <span class="property-indicator"></span>
        <span class="property-type">string[]?</span>
    </dt>
    <dd>{{% md %}}{{% /md %}}</dd>

    <dt class="property-optional"
            title="Optional">
        <span>enable<wbr>Monitoring</span>
        <span class="property-indicator"></span>
        <span class="property-type">boolean?</span>
    </dt>
    <dd>{{% md %}}Indicates whether monitoring is enabled for the instance.
{{% /md %}}</dd>

    <dt class="property-optional"
            title="Optional">
        <span>ephemeral<wbr>Block<wbr>Devices</span>
        <span class="property-indicator"></span>
        <span class="property-type"><a href="#elastigroupephemeralblockdevice">Elastigroup<wbr>Ephemeral<wbr>Block<wbr>Device[]?</a></span>
    </dt>
    <dd>{{% md %}}{{% /md %}}</dd>

    <dt class="property-required"
            title="Required">
        <span>fallback<wbr>To<wbr>Ondemand</span>
        <span class="property-indicator"></span>
        <span class="property-type">boolean</span>
    </dt>
    <dd>{{% md %}}In a case of no Spot instances available, Elastigroup will launch on-demand instances instead.
{{% /md %}}</dd>

    <dt class="property-optional"
            title="Optional">
        <span>health<wbr>Check<wbr>Grace<wbr>Period</span>
        <span class="property-indicator"></span>
        <span class="property-type">number?</span>
    </dt>
    <dd>{{% md %}}The amount of time, in seconds, after the instance has launched to starts and check its health.
{{% /md %}}</dd>

    <dt class="property-optional"
            title="Optional">
        <span>health<wbr>Check<wbr>Type</span>
        <span class="property-indicator"></span>
        <span class="property-type">string?</span>
    </dt>
    <dd>{{% md %}}The service that will perform health checks for the instance. Valid values: `"ELB"`, `"HCS"`, `"TARGET_GROUP"`, `"MLB"`, `"EC2"`, `"MULTAI_TARGET_SET"`, `"MLB_RUNTIME"`, `"K8S_NODE"`, `"NOMAD_NODE"`, `"ECS_CLUSTER_INSTANCE"`.
{{% /md %}}</dd>

    <dt class="property-optional"
            title="Optional">
        <span>health<wbr>Check<wbr>Unhealthy<wbr>Duration<wbr>Before<wbr>Replacement</span>
        <span class="property-indicator"></span>
        <span class="property-type">number?</span>
    </dt>
    <dd>{{% md %}}The amount of time, in seconds, that we will wait before replacing an instance that is running and became unhealthy (this is only applicable for instances that were once healthy).
{{% /md %}}</dd>

    <dt class="property-optional"
            title="Optional">
        <span>iam<wbr>Instance<wbr>Profile</span>
        <span class="property-indicator"></span>
        <span class="property-type">string?</span>
    </dt>
    <dd>{{% md %}}The ARN or name of an IAM instance profile to associate with launched instances.
{{% /md %}}</dd>

    <dt class="property-optional"
            title="Optional">
        <span>image<wbr>Id</span>
        <span class="property-indicator"></span>
        <span class="property-type">string?</span>
    </dt>
    <dd>{{% md %}}The ID of the AMI used to launch the instance.
{{% /md %}}</dd>

    <dt class="property-required"
            title="Required">
        <span>instance<wbr>Types<wbr>Ondemand</span>
        <span class="property-indicator"></span>
        <span class="property-type">string</span>
    </dt>
    <dd>{{% md %}}The type of instance determines your instance's CPU capacity, memory and storage (e.g., m1.small, c1.xlarge).
{{% /md %}}</dd>

    <dt class="property-optional"
            title="Optional">
        <span>instance<wbr>Types<wbr>Preferred<wbr>Spots</span>
        <span class="property-indicator"></span>
        <span class="property-type">string[]?</span>
    </dt>
    <dd>{{% md %}}Prioritize a subset of spot instance types. Must be a subset of the selected spot instance types.
{{% /md %}}</dd>

    <dt class="property-required"
            title="Required">
        <span>instance<wbr>Types<wbr>Spots</span>
        <span class="property-indicator"></span>
        <span class="property-type">string[]</span>
    </dt>
    <dd>{{% md %}}One or more instance types.
{{% /md %}}</dd>

    <dt class="property-optional"
            title="Optional">
        <span>instance<wbr>Types<wbr>Weights</span>
        <span class="property-indicator"></span>
        <span class="property-type"><a href="#elastigroupinstancetypesweight">Elastigroup<wbr>Instance<wbr>Types<wbr>Weight[]?</a></span>
    </dt>
    <dd>{{% md %}}List of weights per instance type for weighted groups. Each object in the list should have the following attributes:
{{% /md %}}</dd>

    <dt class="property-optional"
            title="Optional">
        <span>integration<wbr>Beanstalk</span>
        <span class="property-indicator"></span>
        <span class="property-type"><a href="#elastigroupintegrationbeanstalk">Elastigroup<wbr>Integration<wbr>Beanstalk?</a></span>
    </dt>
    <dd>{{% md %}}{{% /md %}}</dd>

    <dt class="property-optional"
            title="Optional">
        <span>integration<wbr>Codedeploy</span>
        <span class="property-indicator"></span>
        <span class="property-type"><a href="#elastigroupintegrationcodedeploy">Elastigroup<wbr>Integration<wbr>Codedeploy?</a></span>
    </dt>
    <dd>{{% md %}}{{% /md %}}</dd>

    <dt class="property-optional"
            title="Optional">
        <span>integration<wbr>Docker<wbr>Swarm</span>
        <span class="property-indicator"></span>
        <span class="property-type"><a href="#elastigroupintegrationdockerswarm">Elastigroup<wbr>Integration<wbr>Docker<wbr>Swarm?</a></span>
    </dt>
    <dd>{{% md %}}{{% /md %}}</dd>

    <dt class="property-optional"
            title="Optional">
        <span>integration<wbr>Ecs</span>
        <span class="property-indicator"></span>
        <span class="property-type"><a href="#elastigroupintegrationecs">Elastigroup<wbr>Integration<wbr>Ecs?</a></span>
    </dt>
    <dd>{{% md %}}{{% /md %}}</dd>

    <dt class="property-optional"
            title="Optional">
        <span>integration<wbr>Gitlab</span>
        <span class="property-indicator"></span>
        <span class="property-type"><a href="#elastigroupintegrationgitlab">Elastigroup<wbr>Integration<wbr>Gitlab?</a></span>
    </dt>
    <dd>{{% md %}}{{% /md %}}</dd>

    <dt class="property-optional"
            title="Optional">
        <span>integration<wbr>Kubernetes</span>
        <span class="property-indicator"></span>
        <span class="property-type"><a href="#elastigroupintegrationkubernetes">Elastigroup<wbr>Integration<wbr>Kubernetes?</a></span>
    </dt>
    <dd>{{% md %}}{{% /md %}}</dd>

    <dt class="property-optional"
            title="Optional">
        <span>integration<wbr>Mesosphere</span>
        <span class="property-indicator"></span>
        <span class="property-type"><a href="#elastigroupintegrationmesosphere">Elastigroup<wbr>Integration<wbr>Mesosphere?</a></span>
    </dt>
    <dd>{{% md %}}{{% /md %}}</dd>

    <dt class="property-optional"
            title="Optional">
        <span>integration<wbr>Multai<wbr>Runtime</span>
        <span class="property-indicator"></span>
        <span class="property-type"><a href="#elastigroupintegrationmultairuntime">Elastigroup<wbr>Integration<wbr>Multai<wbr>Runtime?</a></span>
    </dt>
    <dd>{{% md %}}{{% /md %}}</dd>

    <dt class="property-optional"
            title="Optional">
        <span>integration<wbr>Nomad</span>
        <span class="property-indicator"></span>
        <span class="property-type"><a href="#elastigroupintegrationnomad">Elastigroup<wbr>Integration<wbr>Nomad?</a></span>
    </dt>
    <dd>{{% md %}}{{% /md %}}</dd>

    <dt class="property-optional"
            title="Optional">
        <span>integration<wbr>Rancher</span>
        <span class="property-indicator"></span>
        <span class="property-type"><a href="#elastigroupintegrationrancher">Elastigroup<wbr>Integration<wbr>Rancher?</a></span>
    </dt>
    <dd>{{% md %}}{{% /md %}}</dd>

    <dt class="property-optional"
            title="Optional">
        <span>integration<wbr>Route53</span>
        <span class="property-indicator"></span>
        <span class="property-type"><a href="#elastigroupintegrationroute53">Elastigroup<wbr>Integration<wbr>Route53?</a></span>
    </dt>
    <dd>{{% md %}}{{% /md %}}</dd>

    <dt class="property-optional"
            title="Optional">
        <span>key<wbr>Name</span>
        <span class="property-indicator"></span>
        <span class="property-type">string?</span>
    </dt>
    <dd>{{% md %}}The key name that should be used for the instance.
{{% /md %}}</dd>

    <dt class="property-optional"
            title="Optional">
        <span>lifetime<wbr>Period</span>
        <span class="property-indicator"></span>
        <span class="property-type">string?</span>
    </dt>
    <dd>{{% md %}}{{% /md %}}</dd>

    <dt class="property-optional"
            title="Optional">
        <span>max<wbr>Size</span>
        <span class="property-indicator"></span>
        <span class="property-type">number?</span>
    </dt>
    <dd>{{% md %}}The maximum number of instances the group should have at any time.
{{% /md %}}</dd>

    <dt class="property-optional"
            title="Optional">
        <span>min<wbr>Size</span>
        <span class="property-indicator"></span>
        <span class="property-type">number?</span>
    </dt>
    <dd>{{% md %}}The minimum number of instances the group should have at any time.
{{% /md %}}</dd>

    <dt class="property-optional"
            title="Optional">
        <span>multai<wbr>Target<wbr>Sets</span>
        <span class="property-indicator"></span>
        <span class="property-type"><a href="#elastigroupmultaitargetset">Elastigroup<wbr>Multai<wbr>Target<wbr>Set[]?</a></span>
    </dt>
    <dd>{{% md %}}{{% /md %}}</dd>

    <dt class="property-optional"
            title="Optional">
        <span>name</span>
        <span class="property-indicator"></span>
        <span class="property-type">string?</span>
    </dt>
    <dd>{{% md %}}The group name.
{{% /md %}}</dd>

    <dt class="property-optional"
            title="Optional">
        <span>network<wbr>Interfaces</span>
        <span class="property-indicator"></span>
        <span class="property-type"><a href="#elastigroupnetworkinterface">Elastigroup<wbr>Network<wbr>Interface[]?</a></span>
    </dt>
    <dd>{{% md %}}{{% /md %}}</dd>

    <dt class="property-optional"
            title="Optional">
        <span>ondemand<wbr>Count</span>
        <span class="property-indicator"></span>
        <span class="property-type">number?</span>
    </dt>
    <dd>{{% md %}}Number of on demand instances to launch in the group. All other instances will be spot instances. When this parameter is set the `spot_percentage` parameter is being ignored.
{{% /md %}}</dd>

    <dt class="property-required"
            title="Required">
        <span>orientation</span>
        <span class="property-indicator"></span>
        <span class="property-type">string</span>
    </dt>
    <dd>{{% md %}}Select a prediction strategy. Valid values: `"balanced"`, `"costOriented"`, `"equalAzDistribution"`, `"availabilityOriented"`.    
{{% /md %}}</dd>

    <dt class="property-optional"
            title="Optional">
        <span>persist<wbr>Block<wbr>Devices</span>
        <span class="property-indicator"></span>
        <span class="property-type">boolean?</span>
    </dt>
    <dd>{{% md %}}{{% /md %}}</dd>

    <dt class="property-optional"
            title="Optional">
        <span>persist<wbr>Private<wbr>Ip</span>
        <span class="property-indicator"></span>
        <span class="property-type">boolean?</span>
    </dt>
    <dd>{{% md %}}{{% /md %}}</dd>

    <dt class="property-optional"
            title="Optional">
        <span>persist<wbr>Root<wbr>Device</span>
        <span class="property-indicator"></span>
        <span class="property-type">boolean?</span>
    </dt>
    <dd>{{% md %}}{{% /md %}}</dd>

    <dt class="property-optional"
            title="Optional">
        <span>placement<wbr>Tenancy</span>
        <span class="property-indicator"></span>
        <span class="property-type">string?</span>
    </dt>
    <dd>{{% md %}}Enable dedicated tenancy. Note: There is a flat hourly fee for each region in which dedicated tenancy is used.
{{% /md %}}</dd>

    <dt class="property-optional"
            title="Optional">
        <span>preferred<wbr>Availability<wbr>Zones</span>
        <span class="property-indicator"></span>
        <span class="property-type">string[]?</span>
    </dt>
    <dd>{{% md %}}The AZs to prioritize when launching Spot instances. If no markets are available in the Preferred AZs, Spot instances are launched in the non-preferred AZs. 
Note: Must be a sublist of `availability_zones` and `orientation` value must not be `"equalAzDistribution"`.
{{% /md %}}</dd>

    <dt class="property-optional"
            title="Optional">
        <span>private<wbr>Ips</span>
        <span class="property-indicator"></span>
        <span class="property-type">string[]?</span>
    </dt>
    <dd>{{% md %}}{{% /md %}}</dd>

    <dt class="property-required"
            title="Required">
        <span>product</span>
        <span class="property-indicator"></span>
        <span class="property-type">string</span>
    </dt>
    <dd>{{% md %}}Operation system type. Valid values: `"Linux/UNIX"`, `"SUSE Linux"`, `"Windows"`. 
For EC2 Classic instances:  `"Linux/UNIX (Amazon VPC)"`, `"SUSE Linux (Amazon VPC)"`, `"Windows (Amazon VPC)"`.
{{% /md %}}</dd>

    <dt class="property-optional"
            title="Optional">
        <span>region</span>
        <span class="property-indicator"></span>
        <span class="property-type">string?</span>
    </dt>
    <dd>{{% md %}}The AWS region your group will be created in.
Note: This parameter is required if you specify subnets (through subnet_ids). This parameter is optional if you specify Availability Zones (through availability_zones).
{{% /md %}}</dd>

    <dt class="property-optional"
            title="Optional">
        <span>revert<wbr>To<wbr>Spot</span>
        <span class="property-indicator"></span>
        <span class="property-type"><a href="#elastigroupreverttospot">Elastigroup<wbr>Revert<wbr>To<wbr>Spot?</a></span>
    </dt>
    <dd>{{% md %}}Hold settings for strategy correction – replacing On-Demand for Spot instances. Supported Values: `"never"`, `"always"`, `"timeWindow"`
{{% /md %}}</dd>

    <dt class="property-optional"
            title="Optional">
        <span>scaling<wbr>Down<wbr>Policies</span>
        <span class="property-indicator"></span>
        <span class="property-type"><a href="#elastigroupscalingdownpolicy">Elastigroup<wbr>Scaling<wbr>Down<wbr>Policy[]?</a></span>
    </dt>
    <dd>{{% md %}}{{% /md %}}</dd>

    <dt class="property-optional"
            title="Optional">
        <span>scaling<wbr>Strategies</span>
        <span class="property-indicator"></span>
        <span class="property-type"><a href="#elastigroupscalingstrategy">Elastigroup<wbr>Scaling<wbr>Strategy[]?</a></span>
    </dt>
    <dd>{{% md %}}Set termination policy.
{{% /md %}}</dd>

    <dt class="property-optional"
            title="Optional">
        <span>scaling<wbr>Target<wbr>Policies</span>
        <span class="property-indicator"></span>
        <span class="property-type"><a href="#elastigroupscalingtargetpolicy">Elastigroup<wbr>Scaling<wbr>Target<wbr>Policy[]?</a></span>
    </dt>
    <dd>{{% md %}}{{% /md %}}</dd>

    <dt class="property-optional"
            title="Optional">
        <span>scaling<wbr>Up<wbr>Policies</span>
        <span class="property-indicator"></span>
        <span class="property-type"><a href="#elastigroupscalinguppolicy">Elastigroup<wbr>Scaling<wbr>Up<wbr>Policy[]?</a></span>
    </dt>
    <dd>{{% md %}}{{% /md %}}</dd>

    <dt class="property-optional"
            title="Optional">
        <span>scheduled<wbr>Tasks</span>
        <span class="property-indicator"></span>
        <span class="property-type"><a href="#elastigroupscheduledtask">Elastigroup<wbr>Scheduled<wbr>Task[]?</a></span>
    </dt>
    <dd>{{% md %}}{{% /md %}}</dd>

    <dt class="property-required"
            title="Required">
        <span>security<wbr>Groups</span>
        <span class="property-indicator"></span>
        <span class="property-type">string[]</span>
    </dt>
    <dd>{{% md %}}A list of associated security group IDS.
{{% /md %}}</dd>

    <dt class="property-optional"
            title="Optional">
        <span>shutdown<wbr>Script</span>
        <span class="property-indicator"></span>
        <span class="property-type">string?</span>
    </dt>
    <dd>{{% md %}}The Base64-encoded shutdown script that executes prior to instance termination, for more information please see: [Shutdown Script](https://api.spotinst.com/integration-docs/elastigroup/concepts/compute-concepts/shutdown-scripts/)
{{% /md %}}</dd>

    <dt class="property-optional"
            title="Optional">
        <span>signals</span>
        <span class="property-indicator"></span>
        <span class="property-type"><a href="#elastigroupsignal">Elastigroup<wbr>Signal[]?</a></span>
    </dt>
    <dd>{{% md %}}{{% /md %}}</dd>

    <dt class="property-optional"
            title="Optional">
        <span>spot<wbr>Percentage</span>
        <span class="property-indicator"></span>
        <span class="property-type">number?</span>
    </dt>
    <dd>{{% md %}}The percentage of Spot instances that would spin up from the `desired_capacity` number.
{{% /md %}}</dd>

    <dt class="property-optional"
            title="Optional">
        <span>stateful<wbr>Deallocation</span>
        <span class="property-indicator"></span>
        <span class="property-type"><a href="#elastigroupstatefuldeallocation">Elastigroup<wbr>Stateful<wbr>Deallocation?</a></span>
    </dt>
    <dd>{{% md %}}{{% /md %}}</dd>

    <dt class="property-optional"
            title="Optional">
        <span>subnet<wbr>Ids</span>
        <span class="property-indicator"></span>
        <span class="property-type">string[]?</span>
    </dt>
    <dd>{{% md %}}List of Strings of subnet identifiers.
Note: When this parameter is set, `availability_zones` should be left unused.
{{% /md %}}</dd>

    <dt class="property-optional"
            title="Optional">
        <span>tags</span>
        <span class="property-indicator"></span>
        <span class="property-type"><a href="#elastigrouptag">Elastigroup<wbr>Tag[]?</a></span>
    </dt>
    <dd>{{% md %}}A key/value mapping of tags to assign to the resource.
{{% /md %}}</dd>

    <dt class="property-optional"
            title="Optional">
        <span>target<wbr>Group<wbr>Arns</span>
        <span class="property-indicator"></span>
        <span class="property-type">string[]?</span>
    </dt>
    <dd>{{% md %}}{{% /md %}}</dd>

    <dt class="property-optional"
            title="Optional">
        <span>update<wbr>Policy</span>
        <span class="property-indicator"></span>
        <span class="property-type"><a href="#elastigroupupdatepolicy">Elastigroup<wbr>Update<wbr>Policy?</a></span>
    </dt>
    <dd>{{% md %}}{{% /md %}}</dd>

    <dt class="property-optional"
            title="Optional">
        <span>user<wbr>Data</span>
        <span class="property-indicator"></span>
        <span class="property-type">string?</span>
    </dt>
    <dd>{{% md %}}The user data to provide when launching the instance.
{{% /md %}}</dd>

    <dt class="property-optional"
            title="Optional">
        <span>utilize<wbr>Reserved<wbr>Instances</span>
        <span class="property-indicator"></span>
        <span class="property-type">boolean?</span>
    </dt>
    <dd>{{% md %}}In a case of any available reserved instances, Elastigroup will utilize them first before purchasing Spot instances.
{{% /md %}}</dd>

    <dt class="property-optional"
            title="Optional">
        <span>wait<wbr>For<wbr>Capacity</span>
        <span class="property-indicator"></span>
        <span class="property-type">number?</span>
    </dt>
    <dd>{{% md %}}Minimum number of instances in a 'HEALTHY' status that is required before continuing. This is ignored when updating with blue/green deployment. Cannot exceed `desired_capacity`.
{{% /md %}}</dd>

    <dt class="property-optional"
            title="Optional">
        <span>wait<wbr>For<wbr>Capacity<wbr>Timeout</span>
        <span class="property-indicator"></span>
        <span class="property-type">number?</span>
    </dt>
    <dd>{{% md %}}Time (seconds) to wait for instances to report a 'HEALTHY' status. Useful for plans with multiple dependencies that take some time to initialize. Leave undefined or set to `0` to indicate no wait. This is ignored when updating with blue/green deployment. 
{{% /md %}}</dd>

</dl>
{{% /choosable %}}


{{% choosable language python %}}
<dl class="resources-properties">

    <dt class="property-optional"
            title="Optional">
        <span>availability_<wbr>zones</span>
        <span class="property-indicator"></span>
        <span class="property-type">List[str]</span>
    </dt>
    <dd>{{% md %}}List of Strings of availability zones. When this parameter is set, `subnet_ids` should be left unused.
Note: `availability_zones` naming syntax follows the convention `availability-zone:subnet:placement-group-name`. For example, to set an AZ in `us-east-1` with subnet `subnet-123456` and placement group `ClusterI03`, you would set:
`availability_zones = ["us-east-1a:subnet-123456:ClusterI03"]`
{{% /md %}}</dd>

    <dt class="property-optional"
            title="Optional">
        <span>block_<wbr>devices_<wbr>mode</span>
        <span class="property-indicator"></span>
        <span class="property-type">str</span>
    </dt>
    <dd>{{% md %}}{{% /md %}}</dd>

    <dt class="property-optional"
            title="Optional">
        <span>capacity_<wbr>unit</span>
        <span class="property-indicator"></span>
        <span class="property-type">str</span>
    </dt>
    <dd>{{% md %}}The capacity unit to launch instances by. If not specified, when choosing the weight unit, each instance will weight as the number of its vCPUs.
{{% /md %}}</dd>

    <dt class="property-optional"
            title="Optional">
        <span>cpu_<wbr>credits</span>
        <span class="property-indicator"></span>
        <span class="property-type">str</span>
    </dt>
    <dd>{{% md %}}Controls how T3 instances are launched. Valid values: `standard`, `unlimited`.
{{% /md %}}</dd>

    <dt class="property-optional"
            title="Optional">
        <span>description</span>
        <span class="property-indicator"></span>
        <span class="property-type">str</span>
    </dt>
    <dd>{{% md %}}The group description.
{{% /md %}}</dd>

    <dt class="property-optional"
            title="Optional">
        <span>desired_<wbr>capacity</span>
        <span class="property-indicator"></span>
        <span class="property-type">float</span>
    </dt>
    <dd>{{% md %}}The desired number of instances the group should have at any time.
{{% /md %}}</dd>

    <dt class="property-optional"
            title="Optional">
        <span>draining_<wbr>timeout</span>
        <span class="property-indicator"></span>
        <span class="property-type">float</span>
    </dt>
    <dd>{{% md %}}The time in seconds, the instance is allowed to run while detached from the ELB. This is to allow the instance time to be drained from incoming TCP connections before terminating it, during a scale down operation.
{{% /md %}}</dd>

    <dt class="property-optional"
            title="Optional">
        <span>ebs_<wbr>block_<wbr>devices</span>
        <span class="property-indicator"></span>
        <span class="property-type"><a href="#elastigroupebsblockdevice">List[Elastigroup<wbr>Ebs<wbr>Block<wbr>Device]</a></span>
    </dt>
    <dd>{{% md %}}{{% /md %}}</dd>

    <dt class="property-optional"
            title="Optional">
        <span>ebs_<wbr>optimized</span>
        <span class="property-indicator"></span>
        <span class="property-type">bool</span>
    </dt>
    <dd>{{% md %}}Enable high bandwidth connectivity between instances and AWS’s Elastic Block Store (EBS). For instance types that are EBS-optimized by default this parameter will be ignored.
{{% /md %}}</dd>

    <dt class="property-optional"
            title="Optional">
        <span>elastic_<wbr>ips</span>
        <span class="property-indicator"></span>
        <span class="property-type">List[str]</span>
    </dt>
    <dd>{{% md %}}A list of [AWS Elastic IP](http://docs.aws.amazon.com/AWSEC2/latest/UserGuide/elastic-ip-addresses-eip.html) allocation IDs to associate to the group instances.
{{% /md %}}</dd>

    <dt class="property-optional"
            title="Optional">
        <span>elastic_<wbr>load_<wbr>balancers</span>
        <span class="property-indicator"></span>
        <span class="property-type">List[str]</span>
    </dt>
    <dd>{{% md %}}{{% /md %}}</dd>

    <dt class="property-optional"
            title="Optional">
        <span>enable_<wbr>monitoring</span>
        <span class="property-indicator"></span>
        <span class="property-type">bool</span>
    </dt>
    <dd>{{% md %}}Indicates whether monitoring is enabled for the instance.
{{% /md %}}</dd>

    <dt class="property-optional"
            title="Optional">
        <span>ephemeral_<wbr>block_<wbr>devices</span>
        <span class="property-indicator"></span>
        <span class="property-type"><a href="#elastigroupephemeralblockdevice">List[Elastigroup<wbr>Ephemeral<wbr>Block<wbr>Device]</a></span>
    </dt>
    <dd>{{% md %}}{{% /md %}}</dd>

    <dt class="property-required"
            title="Required">
        <span>fallback_<wbr>to_<wbr>ondemand</span>
        <span class="property-indicator"></span>
        <span class="property-type">bool</span>
    </dt>
    <dd>{{% md %}}In a case of no Spot instances available, Elastigroup will launch on-demand instances instead.
{{% /md %}}</dd>

    <dt class="property-optional"
            title="Optional">
        <span>health_<wbr>check_<wbr>grace_<wbr>period</span>
        <span class="property-indicator"></span>
        <span class="property-type">float</span>
    </dt>
    <dd>{{% md %}}The amount of time, in seconds, after the instance has launched to starts and check its health.
{{% /md %}}</dd>

    <dt class="property-optional"
            title="Optional">
        <span>health_<wbr>check_<wbr>type</span>
        <span class="property-indicator"></span>
        <span class="property-type">str</span>
    </dt>
    <dd>{{% md %}}The service that will perform health checks for the instance. Valid values: `"ELB"`, `"HCS"`, `"TARGET_GROUP"`, `"MLB"`, `"EC2"`, `"MULTAI_TARGET_SET"`, `"MLB_RUNTIME"`, `"K8S_NODE"`, `"NOMAD_NODE"`, `"ECS_CLUSTER_INSTANCE"`.
{{% /md %}}</dd>

    <dt class="property-optional"
            title="Optional">
        <span>health_<wbr>check_<wbr>unhealthy_<wbr>duration_<wbr>before_<wbr>replacement</span>
        <span class="property-indicator"></span>
        <span class="property-type">float</span>
    </dt>
    <dd>{{% md %}}The amount of time, in seconds, that we will wait before replacing an instance that is running and became unhealthy (this is only applicable for instances that were once healthy).
{{% /md %}}</dd>

    <dt class="property-optional"
            title="Optional">
        <span>iam_<wbr>instance_<wbr>profile</span>
        <span class="property-indicator"></span>
        <span class="property-type">str</span>
    </dt>
    <dd>{{% md %}}The ARN or name of an IAM instance profile to associate with launched instances.
{{% /md %}}</dd>

    <dt class="property-optional"
            title="Optional">
        <span>image_<wbr>id</span>
        <span class="property-indicator"></span>
        <span class="property-type">str</span>
    </dt>
    <dd>{{% md %}}The ID of the AMI used to launch the instance.
{{% /md %}}</dd>

    <dt class="property-required"
            title="Required">
        <span>instance_<wbr>types_<wbr>ondemand</span>
        <span class="property-indicator"></span>
        <span class="property-type">str</span>
    </dt>
    <dd>{{% md %}}The type of instance determines your instance's CPU capacity, memory and storage (e.g., m1.small, c1.xlarge).
{{% /md %}}</dd>

    <dt class="property-optional"
            title="Optional">
        <span>instance_<wbr>types_<wbr>preferred_<wbr>spots</span>
        <span class="property-indicator"></span>
        <span class="property-type">List[str]</span>
    </dt>
    <dd>{{% md %}}Prioritize a subset of spot instance types. Must be a subset of the selected spot instance types.
{{% /md %}}</dd>

    <dt class="property-required"
            title="Required">
        <span>instance_<wbr>types_<wbr>spots</span>
        <span class="property-indicator"></span>
        <span class="property-type">List[str]</span>
    </dt>
    <dd>{{% md %}}One or more instance types.
{{% /md %}}</dd>

    <dt class="property-optional"
            title="Optional">
        <span>instance_<wbr>types_<wbr>weights</span>
        <span class="property-indicator"></span>
        <span class="property-type"><a href="#elastigroupinstancetypesweight">List[Elastigroup<wbr>Instance<wbr>Types<wbr>Weight]</a></span>
    </dt>
    <dd>{{% md %}}List of weights per instance type for weighted groups. Each object in the list should have the following attributes:
{{% /md %}}</dd>

    <dt class="property-optional"
            title="Optional">
        <span>integration_<wbr>beanstalk</span>
        <span class="property-indicator"></span>
        <span class="property-type"><a href="#elastigroupintegrationbeanstalk">Dict[Elastigroup<wbr>Integration<wbr>Beanstalk]</a></span>
    </dt>
    <dd>{{% md %}}{{% /md %}}</dd>

    <dt class="property-optional"
            title="Optional">
        <span>integration_<wbr>codedeploy</span>
        <span class="property-indicator"></span>
        <span class="property-type"><a href="#elastigroupintegrationcodedeploy">Dict[Elastigroup<wbr>Integration<wbr>Codedeploy]</a></span>
    </dt>
    <dd>{{% md %}}{{% /md %}}</dd>

    <dt class="property-optional"
            title="Optional">
        <span>integration_<wbr>docker_<wbr>swarm</span>
        <span class="property-indicator"></span>
        <span class="property-type"><a href="#elastigroupintegrationdockerswarm">Dict[Elastigroup<wbr>Integration<wbr>Docker<wbr>Swarm]</a></span>
    </dt>
    <dd>{{% md %}}{{% /md %}}</dd>

    <dt class="property-optional"
            title="Optional">
        <span>integration_<wbr>ecs</span>
        <span class="property-indicator"></span>
        <span class="property-type"><a href="#elastigroupintegrationecs">Dict[Elastigroup<wbr>Integration<wbr>Ecs]</a></span>
    </dt>
    <dd>{{% md %}}{{% /md %}}</dd>

    <dt class="property-optional"
            title="Optional">
        <span>integration_<wbr>gitlab</span>
        <span class="property-indicator"></span>
        <span class="property-type"><a href="#elastigroupintegrationgitlab">Dict[Elastigroup<wbr>Integration<wbr>Gitlab]</a></span>
    </dt>
    <dd>{{% md %}}{{% /md %}}</dd>

    <dt class="property-optional"
            title="Optional">
        <span>integration_<wbr>kubernetes</span>
        <span class="property-indicator"></span>
        <span class="property-type"><a href="#elastigroupintegrationkubernetes">Dict[Elastigroup<wbr>Integration<wbr>Kubernetes]</a></span>
    </dt>
    <dd>{{% md %}}{{% /md %}}</dd>

    <dt class="property-optional"
            title="Optional">
        <span>integration_<wbr>mesosphere</span>
        <span class="property-indicator"></span>
        <span class="property-type"><a href="#elastigroupintegrationmesosphere">Dict[Elastigroup<wbr>Integration<wbr>Mesosphere]</a></span>
    </dt>
    <dd>{{% md %}}{{% /md %}}</dd>

    <dt class="property-optional"
            title="Optional">
        <span>integration_<wbr>multai_<wbr>runtime</span>
        <span class="property-indicator"></span>
        <span class="property-type"><a href="#elastigroupintegrationmultairuntime">Dict[Elastigroup<wbr>Integration<wbr>Multai<wbr>Runtime]</a></span>
    </dt>
    <dd>{{% md %}}{{% /md %}}</dd>

    <dt class="property-optional"
            title="Optional">
        <span>integration_<wbr>nomad</span>
        <span class="property-indicator"></span>
        <span class="property-type"><a href="#elastigroupintegrationnomad">Dict[Elastigroup<wbr>Integration<wbr>Nomad]</a></span>
    </dt>
    <dd>{{% md %}}{{% /md %}}</dd>

    <dt class="property-optional"
            title="Optional">
        <span>integration_<wbr>rancher</span>
        <span class="property-indicator"></span>
        <span class="property-type"><a href="#elastigroupintegrationrancher">Dict[Elastigroup<wbr>Integration<wbr>Rancher]</a></span>
    </dt>
    <dd>{{% md %}}{{% /md %}}</dd>

    <dt class="property-optional"
            title="Optional">
        <span>integration_<wbr>route53</span>
        <span class="property-indicator"></span>
        <span class="property-type"><a href="#elastigroupintegrationroute53">Dict[Elastigroup<wbr>Integration<wbr>Route53]</a></span>
    </dt>
    <dd>{{% md %}}{{% /md %}}</dd>

    <dt class="property-optional"
            title="Optional">
        <span>key_<wbr>name</span>
        <span class="property-indicator"></span>
        <span class="property-type">str</span>
    </dt>
    <dd>{{% md %}}The key name that should be used for the instance.
{{% /md %}}</dd>

    <dt class="property-optional"
            title="Optional">
        <span>lifetime_<wbr>period</span>
        <span class="property-indicator"></span>
        <span class="property-type">str</span>
    </dt>
    <dd>{{% md %}}{{% /md %}}</dd>

    <dt class="property-optional"
            title="Optional">
        <span>max_<wbr>size</span>
        <span class="property-indicator"></span>
        <span class="property-type">float</span>
    </dt>
    <dd>{{% md %}}The maximum number of instances the group should have at any time.
{{% /md %}}</dd>

    <dt class="property-optional"
            title="Optional">
        <span>min_<wbr>size</span>
        <span class="property-indicator"></span>
        <span class="property-type">float</span>
    </dt>
    <dd>{{% md %}}The minimum number of instances the group should have at any time.
{{% /md %}}</dd>

    <dt class="property-optional"
            title="Optional">
        <span>multai_<wbr>target_<wbr>sets</span>
        <span class="property-indicator"></span>
        <span class="property-type"><a href="#elastigroupmultaitargetset">List[Elastigroup<wbr>Multai<wbr>Target<wbr>Set]</a></span>
    </dt>
    <dd>{{% md %}}{{% /md %}}</dd>

    <dt class="property-optional"
            title="Optional">
        <span>name</span>
        <span class="property-indicator"></span>
        <span class="property-type">str</span>
    </dt>
    <dd>{{% md %}}The group name.
{{% /md %}}</dd>

    <dt class="property-optional"
            title="Optional">
        <span>network_<wbr>interfaces</span>
        <span class="property-indicator"></span>
        <span class="property-type"><a href="#elastigroupnetworkinterface">List[Elastigroup<wbr>Network<wbr>Interface]</a></span>
    </dt>
    <dd>{{% md %}}{{% /md %}}</dd>

    <dt class="property-optional"
            title="Optional">
        <span>ondemand_<wbr>count</span>
        <span class="property-indicator"></span>
        <span class="property-type">float</span>
    </dt>
    <dd>{{% md %}}Number of on demand instances to launch in the group. All other instances will be spot instances. When this parameter is set the `spot_percentage` parameter is being ignored.
{{% /md %}}</dd>

    <dt class="property-required"
            title="Required">
        <span>orientation</span>
        <span class="property-indicator"></span>
        <span class="property-type">str</span>
    </dt>
    <dd>{{% md %}}Select a prediction strategy. Valid values: `"balanced"`, `"costOriented"`, `"equalAzDistribution"`, `"availabilityOriented"`.    
{{% /md %}}</dd>

    <dt class="property-optional"
            title="Optional">
        <span>persist_<wbr>block_<wbr>devices</span>
        <span class="property-indicator"></span>
        <span class="property-type">bool</span>
    </dt>
    <dd>{{% md %}}{{% /md %}}</dd>

    <dt class="property-optional"
            title="Optional">
        <span>persist_<wbr>private_<wbr>ip</span>
        <span class="property-indicator"></span>
        <span class="property-type">bool</span>
    </dt>
    <dd>{{% md %}}{{% /md %}}</dd>

    <dt class="property-optional"
            title="Optional">
        <span>persist_<wbr>root_<wbr>device</span>
        <span class="property-indicator"></span>
        <span class="property-type">bool</span>
    </dt>
    <dd>{{% md %}}{{% /md %}}</dd>

    <dt class="property-optional"
            title="Optional">
        <span>placement_<wbr>tenancy</span>
        <span class="property-indicator"></span>
        <span class="property-type">str</span>
    </dt>
    <dd>{{% md %}}Enable dedicated tenancy. Note: There is a flat hourly fee for each region in which dedicated tenancy is used.
{{% /md %}}</dd>

    <dt class="property-optional"
            title="Optional">
        <span>preferred_<wbr>availability_<wbr>zones</span>
        <span class="property-indicator"></span>
        <span class="property-type">List[str]</span>
    </dt>
    <dd>{{% md %}}The AZs to prioritize when launching Spot instances. If no markets are available in the Preferred AZs, Spot instances are launched in the non-preferred AZs. 
Note: Must be a sublist of `availability_zones` and `orientation` value must not be `"equalAzDistribution"`.
{{% /md %}}</dd>

    <dt class="property-optional"
            title="Optional">
        <span>private_<wbr>ips</span>
        <span class="property-indicator"></span>
        <span class="property-type">List[str]</span>
    </dt>
    <dd>{{% md %}}{{% /md %}}</dd>

    <dt class="property-required"
            title="Required">
        <span>product</span>
        <span class="property-indicator"></span>
        <span class="property-type">str</span>
    </dt>
    <dd>{{% md %}}Operation system type. Valid values: `"Linux/UNIX"`, `"SUSE Linux"`, `"Windows"`. 
For EC2 Classic instances:  `"Linux/UNIX (Amazon VPC)"`, `"SUSE Linux (Amazon VPC)"`, `"Windows (Amazon VPC)"`.
{{% /md %}}</dd>

    <dt class="property-optional"
            title="Optional">
        <span>region</span>
        <span class="property-indicator"></span>
        <span class="property-type">str</span>
    </dt>
    <dd>{{% md %}}The AWS region your group will be created in.
Note: This parameter is required if you specify subnets (through subnet_ids). This parameter is optional if you specify Availability Zones (through availability_zones).
{{% /md %}}</dd>

    <dt class="property-optional"
            title="Optional">
        <span>revert_<wbr>to_<wbr>spot</span>
        <span class="property-indicator"></span>
        <span class="property-type"><a href="#elastigroupreverttospot">Dict[Elastigroup<wbr>Revert<wbr>To<wbr>Spot]</a></span>
    </dt>
    <dd>{{% md %}}Hold settings for strategy correction – replacing On-Demand for Spot instances. Supported Values: `"never"`, `"always"`, `"timeWindow"`
{{% /md %}}</dd>

    <dt class="property-optional"
            title="Optional">
        <span>scaling_<wbr>down_<wbr>policies</span>
        <span class="property-indicator"></span>
        <span class="property-type"><a href="#elastigroupscalingdownpolicy">List[Elastigroup<wbr>Scaling<wbr>Down<wbr>Policy]</a></span>
    </dt>
    <dd>{{% md %}}{{% /md %}}</dd>

    <dt class="property-optional"
            title="Optional">
        <span>scaling_<wbr>strategies</span>
        <span class="property-indicator"></span>
        <span class="property-type"><a href="#elastigroupscalingstrategy">List[Elastigroup<wbr>Scaling<wbr>Strategy]</a></span>
    </dt>
    <dd>{{% md %}}Set termination policy.
{{% /md %}}</dd>

    <dt class="property-optional"
            title="Optional">
        <span>scaling_<wbr>target_<wbr>policies</span>
        <span class="property-indicator"></span>
        <span class="property-type"><a href="#elastigroupscalingtargetpolicy">List[Elastigroup<wbr>Scaling<wbr>Target<wbr>Policy]</a></span>
    </dt>
    <dd>{{% md %}}{{% /md %}}</dd>

    <dt class="property-optional"
            title="Optional">
        <span>scaling_<wbr>up_<wbr>policies</span>
        <span class="property-indicator"></span>
        <span class="property-type"><a href="#elastigroupscalinguppolicy">List[Elastigroup<wbr>Scaling<wbr>Up<wbr>Policy]</a></span>
    </dt>
    <dd>{{% md %}}{{% /md %}}</dd>

    <dt class="property-optional"
            title="Optional">
        <span>scheduled_<wbr>tasks</span>
        <span class="property-indicator"></span>
        <span class="property-type"><a href="#elastigroupscheduledtask">List[Elastigroup<wbr>Scheduled<wbr>Task]</a></span>
    </dt>
    <dd>{{% md %}}{{% /md %}}</dd>

    <dt class="property-required"
            title="Required">
        <span>security_<wbr>groups</span>
        <span class="property-indicator"></span>
        <span class="property-type">List[str]</span>
    </dt>
    <dd>{{% md %}}A list of associated security group IDS.
{{% /md %}}</dd>

    <dt class="property-optional"
            title="Optional">
        <span>shutdown_<wbr>script</span>
        <span class="property-indicator"></span>
        <span class="property-type">str</span>
    </dt>
    <dd>{{% md %}}The Base64-encoded shutdown script that executes prior to instance termination, for more information please see: [Shutdown Script](https://api.spotinst.com/integration-docs/elastigroup/concepts/compute-concepts/shutdown-scripts/)
{{% /md %}}</dd>

    <dt class="property-optional"
            title="Optional">
        <span>signals</span>
        <span class="property-indicator"></span>
        <span class="property-type"><a href="#elastigroupsignal">List[Elastigroup<wbr>Signal]</a></span>
    </dt>
    <dd>{{% md %}}{{% /md %}}</dd>

    <dt class="property-optional"
            title="Optional">
        <span>spot_<wbr>percentage</span>
        <span class="property-indicator"></span>
        <span class="property-type">float</span>
    </dt>
    <dd>{{% md %}}The percentage of Spot instances that would spin up from the `desired_capacity` number.
{{% /md %}}</dd>

    <dt class="property-optional"
            title="Optional">
        <span>stateful_<wbr>deallocation</span>
        <span class="property-indicator"></span>
        <span class="property-type"><a href="#elastigroupstatefuldeallocation">Dict[Elastigroup<wbr>Stateful<wbr>Deallocation]</a></span>
    </dt>
    <dd>{{% md %}}{{% /md %}}</dd>

    <dt class="property-optional"
            title="Optional">
        <span>subnet_<wbr>ids</span>
        <span class="property-indicator"></span>
        <span class="property-type">List[str]</span>
    </dt>
    <dd>{{% md %}}List of Strings of subnet identifiers.
Note: When this parameter is set, `availability_zones` should be left unused.
{{% /md %}}</dd>

    <dt class="property-optional"
            title="Optional">
        <span>tags</span>
        <span class="property-indicator"></span>
        <span class="property-type"><a href="#elastigrouptag">List[Elastigroup<wbr>Tag]</a></span>
    </dt>
    <dd>{{% md %}}A key/value mapping of tags to assign to the resource.
{{% /md %}}</dd>

    <dt class="property-optional"
            title="Optional">
        <span>target_<wbr>group_<wbr>arns</span>
        <span class="property-indicator"></span>
        <span class="property-type">List[str]</span>
    </dt>
    <dd>{{% md %}}{{% /md %}}</dd>

    <dt class="property-optional"
            title="Optional">
        <span>update_<wbr>policy</span>
        <span class="property-indicator"></span>
        <span class="property-type"><a href="#elastigroupupdatepolicy">Dict[Elastigroup<wbr>Update<wbr>Policy]</a></span>
    </dt>
    <dd>{{% md %}}{{% /md %}}</dd>

    <dt class="property-optional"
            title="Optional">
        <span>user_<wbr>data</span>
        <span class="property-indicator"></span>
        <span class="property-type">str</span>
    </dt>
    <dd>{{% md %}}The user data to provide when launching the instance.
{{% /md %}}</dd>

    <dt class="property-optional"
            title="Optional">
        <span>utilize_<wbr>reserved_<wbr>instances</span>
        <span class="property-indicator"></span>
        <span class="property-type">bool</span>
    </dt>
    <dd>{{% md %}}In a case of any available reserved instances, Elastigroup will utilize them first before purchasing Spot instances.
{{% /md %}}</dd>

    <dt class="property-optional"
            title="Optional">
        <span>wait_<wbr>for_<wbr>capacity</span>
        <span class="property-indicator"></span>
        <span class="property-type">float</span>
    </dt>
    <dd>{{% md %}}Minimum number of instances in a 'HEALTHY' status that is required before continuing. This is ignored when updating with blue/green deployment. Cannot exceed `desired_capacity`.
{{% /md %}}</dd>

    <dt class="property-optional"
            title="Optional">
        <span>wait_<wbr>for_<wbr>capacity_<wbr>timeout</span>
        <span class="property-indicator"></span>
        <span class="property-type">float</span>
    </dt>
    <dd>{{% md %}}Time (seconds) to wait for instances to report a 'HEALTHY' status. Useful for plans with multiple dependencies that take some time to initialize. Leave undefined or set to `0` to indicate no wait. This is ignored when updating with blue/green deployment. 
{{% /md %}}</dd>

</dl>
{{% /choosable %}}







## Elastigroup Output Properties

The following output properties are available:




{{% choosable language csharp %}}
<dl class="resources-properties">

    <dt class="property-"
            title="">
        <span>Availability<wbr>Zones</span>
        <span class="property-indicator"></span>
        <span class="property-type">List<string>?</span>
    </dt>
    <dd>{{% md %}}List of Strings of availability zones. When this parameter is set, `subnet_ids` should be left unused.
Note: `availability_zones` naming syntax follows the convention `availability-zone:subnet:placement-group-name`. For example, to set an AZ in `us-east-1` with subnet `subnet-123456` and placement group `ClusterI03`, you would set:
`availability_zones = ["us-east-1a:subnet-123456:ClusterI03"]`
{{% /md %}}</dd>

    <dt class="property-"
            title="">
        <span>Block<wbr>Devices<wbr>Mode</span>
        <span class="property-indicator"></span>
        <span class="property-type">string?</span>
    </dt>
    <dd>{{% md %}}{{% /md %}}</dd>

    <dt class="property-"
            title="">
        <span>Capacity<wbr>Unit</span>
        <span class="property-indicator"></span>
        <span class="property-type">string</span>
    </dt>
    <dd>{{% md %}}The capacity unit to launch instances by. If not specified, when choosing the weight unit, each instance will weight as the number of its vCPUs.
{{% /md %}}</dd>

    <dt class="property-"
            title="">
        <span>Cpu<wbr>Credits</span>
        <span class="property-indicator"></span>
        <span class="property-type">string?</span>
    </dt>
    <dd>{{% md %}}Controls how T3 instances are launched. Valid values: `standard`, `unlimited`.
{{% /md %}}</dd>

    <dt class="property-"
            title="">
        <span>Description</span>
        <span class="property-indicator"></span>
        <span class="property-type">string?</span>
    </dt>
    <dd>{{% md %}}The group description.
{{% /md %}}</dd>

    <dt class="property-"
            title="">
        <span>Desired<wbr>Capacity</span>
        <span class="property-indicator"></span>
        <span class="property-type">int?</span>
    </dt>
    <dd>{{% md %}}The desired number of instances the group should have at any time.
{{% /md %}}</dd>

    <dt class="property-"
            title="">
        <span>Draining<wbr>Timeout</span>
        <span class="property-indicator"></span>
        <span class="property-type">int</span>
    </dt>
    <dd>{{% md %}}The time in seconds, the instance is allowed to run while detached from the ELB. This is to allow the instance time to be drained from incoming TCP connections before terminating it, during a scale down operation.
{{% /md %}}</dd>

    <dt class="property-"
            title="">
        <span>Ebs<wbr>Block<wbr>Devices</span>
        <span class="property-indicator"></span>
        <span class="property-type"><a href="#elastigroupebsblockdevice">List&lt;Elastigroup<wbr>Ebs<wbr>Block<wbr>Device&gt;?</a></span>
    </dt>
    <dd>{{% md %}}{{% /md %}}</dd>

    <dt class="property-"
            title="">
        <span>Ebs<wbr>Optimized</span>
        <span class="property-indicator"></span>
        <span class="property-type">bool</span>
    </dt>
    <dd>{{% md %}}Enable high bandwidth connectivity between instances and AWS’s Elastic Block Store (EBS). For instance types that are EBS-optimized by default this parameter will be ignored.
{{% /md %}}</dd>

    <dt class="property-"
            title="">
        <span>Elastic<wbr>Ips</span>
        <span class="property-indicator"></span>
        <span class="property-type">List<string>?</span>
    </dt>
    <dd>{{% md %}}A list of [AWS Elastic IP](http://docs.aws.amazon.com/AWSEC2/latest/UserGuide/elastic-ip-addresses-eip.html) allocation IDs to associate to the group instances.
{{% /md %}}</dd>

    <dt class="property-"
            title="">
        <span>Elastic<wbr>Load<wbr>Balancers</span>
        <span class="property-indicator"></span>
        <span class="property-type">List<string>?</span>
    </dt>
    <dd>{{% md %}}{{% /md %}}</dd>

    <dt class="property-"
            title="">
        <span>Enable<wbr>Monitoring</span>
        <span class="property-indicator"></span>
        <span class="property-type">bool?</span>
    </dt>
    <dd>{{% md %}}Indicates whether monitoring is enabled for the instance.
{{% /md %}}</dd>

    <dt class="property-"
            title="">
        <span>Ephemeral<wbr>Block<wbr>Devices</span>
        <span class="property-indicator"></span>
        <span class="property-type"><a href="#elastigroupephemeralblockdevice">List&lt;Elastigroup<wbr>Ephemeral<wbr>Block<wbr>Device&gt;?</a></span>
    </dt>
    <dd>{{% md %}}{{% /md %}}</dd>

    <dt class="property-"
            title="">
        <span>Fallback<wbr>To<wbr>Ondemand</span>
        <span class="property-indicator"></span>
        <span class="property-type">bool</span>
    </dt>
    <dd>{{% md %}}In a case of no Spot instances available, Elastigroup will launch on-demand instances instead.
{{% /md %}}</dd>

    <dt class="property-"
            title="">
        <span>Health<wbr>Check<wbr>Grace<wbr>Period</span>
        <span class="property-indicator"></span>
        <span class="property-type">int?</span>
    </dt>
    <dd>{{% md %}}The amount of time, in seconds, after the instance has launched to starts and check its health.
{{% /md %}}</dd>

    <dt class="property-"
            title="">
        <span>Health<wbr>Check<wbr>Type</span>
        <span class="property-indicator"></span>
        <span class="property-type">string?</span>
    </dt>
    <dd>{{% md %}}The service that will perform health checks for the instance. Valid values: `"ELB"`, `"HCS"`, `"TARGET_GROUP"`, `"MLB"`, `"EC2"`, `"MULTAI_TARGET_SET"`, `"MLB_RUNTIME"`, `"K8S_NODE"`, `"NOMAD_NODE"`, `"ECS_CLUSTER_INSTANCE"`.
{{% /md %}}</dd>

    <dt class="property-"
            title="">
        <span>Health<wbr>Check<wbr>Unhealthy<wbr>Duration<wbr>Before<wbr>Replacement</span>
        <span class="property-indicator"></span>
        <span class="property-type">int?</span>
    </dt>
    <dd>{{% md %}}The amount of time, in seconds, that we will wait before replacing an instance that is running and became unhealthy (this is only applicable for instances that were once healthy).
{{% /md %}}</dd>

    <dt class="property-"
            title="">
        <span>Iam<wbr>Instance<wbr>Profile</span>
        <span class="property-indicator"></span>
        <span class="property-type">string?</span>
    </dt>
    <dd>{{% md %}}The ARN or name of an IAM instance profile to associate with launched instances.
{{% /md %}}</dd>

    <dt class="property-"
            title="">
        <span>Image<wbr>Id</span>
        <span class="property-indicator"></span>
        <span class="property-type">string?</span>
    </dt>
    <dd>{{% md %}}The ID of the AMI used to launch the instance.
{{% /md %}}</dd>

    <dt class="property-"
            title="">
        <span>Instance<wbr>Types<wbr>Ondemand</span>
        <span class="property-indicator"></span>
        <span class="property-type">string</span>
    </dt>
    <dd>{{% md %}}The type of instance determines your instance's CPU capacity, memory and storage (e.g., m1.small, c1.xlarge).
{{% /md %}}</dd>

    <dt class="property-"
            title="">
        <span>Instance<wbr>Types<wbr>Preferred<wbr>Spots</span>
        <span class="property-indicator"></span>
        <span class="property-type">List<string>?</span>
    </dt>
    <dd>{{% md %}}Prioritize a subset of spot instance types. Must be a subset of the selected spot instance types.
{{% /md %}}</dd>

    <dt class="property-"
            title="">
        <span>Instance<wbr>Types<wbr>Spots</span>
        <span class="property-indicator"></span>
        <span class="property-type">List<string></span>
    </dt>
    <dd>{{% md %}}One or more instance types.
{{% /md %}}</dd>

    <dt class="property-"
            title="">
        <span>Instance<wbr>Types<wbr>Weights</span>
        <span class="property-indicator"></span>
        <span class="property-type"><a href="#elastigroupinstancetypesweight">List&lt;Elastigroup<wbr>Instance<wbr>Types<wbr>Weight&gt;?</a></span>
    </dt>
    <dd>{{% md %}}List of weights per instance type for weighted groups. Each object in the list should have the following attributes:
{{% /md %}}</dd>

    <dt class="property-"
            title="">
        <span>Integration<wbr>Beanstalk</span>
        <span class="property-indicator"></span>
        <span class="property-type"><a href="#elastigroupintegrationbeanstalk">Elastigroup<wbr>Integration<wbr>Beanstalk?</a></span>
    </dt>
    <dd>{{% md %}}{{% /md %}}</dd>

    <dt class="property-"
            title="">
        <span>Integration<wbr>Codedeploy</span>
        <span class="property-indicator"></span>
        <span class="property-type"><a href="#elastigroupintegrationcodedeploy">Elastigroup<wbr>Integration<wbr>Codedeploy?</a></span>
    </dt>
    <dd>{{% md %}}{{% /md %}}</dd>

    <dt class="property-"
            title="">
        <span>Integration<wbr>Docker<wbr>Swarm</span>
        <span class="property-indicator"></span>
        <span class="property-type"><a href="#elastigroupintegrationdockerswarm">Elastigroup<wbr>Integration<wbr>Docker<wbr>Swarm?</a></span>
    </dt>
    <dd>{{% md %}}{{% /md %}}</dd>

    <dt class="property-"
            title="">
        <span>Integration<wbr>Ecs</span>
        <span class="property-indicator"></span>
        <span class="property-type"><a href="#elastigroupintegrationecs">Elastigroup<wbr>Integration<wbr>Ecs?</a></span>
    </dt>
    <dd>{{% md %}}{{% /md %}}</dd>

    <dt class="property-"
            title="">
        <span>Integration<wbr>Gitlab</span>
        <span class="property-indicator"></span>
        <span class="property-type"><a href="#elastigroupintegrationgitlab">Elastigroup<wbr>Integration<wbr>Gitlab?</a></span>
    </dt>
    <dd>{{% md %}}{{% /md %}}</dd>

    <dt class="property-"
            title="">
        <span>Integration<wbr>Kubernetes</span>
        <span class="property-indicator"></span>
        <span class="property-type"><a href="#elastigroupintegrationkubernetes">Elastigroup<wbr>Integration<wbr>Kubernetes?</a></span>
    </dt>
    <dd>{{% md %}}{{% /md %}}</dd>

    <dt class="property-"
            title="">
        <span>Integration<wbr>Mesosphere</span>
        <span class="property-indicator"></span>
        <span class="property-type"><a href="#elastigroupintegrationmesosphere">Elastigroup<wbr>Integration<wbr>Mesosphere?</a></span>
    </dt>
    <dd>{{% md %}}{{% /md %}}</dd>

    <dt class="property-"
            title="">
        <span>Integration<wbr>Multai<wbr>Runtime</span>
        <span class="property-indicator"></span>
        <span class="property-type"><a href="#elastigroupintegrationmultairuntime">Elastigroup<wbr>Integration<wbr>Multai<wbr>Runtime?</a></span>
    </dt>
    <dd>{{% md %}}{{% /md %}}</dd>

    <dt class="property-"
            title="">
        <span>Integration<wbr>Nomad</span>
        <span class="property-indicator"></span>
        <span class="property-type"><a href="#elastigroupintegrationnomad">Elastigroup<wbr>Integration<wbr>Nomad?</a></span>
    </dt>
    <dd>{{% md %}}{{% /md %}}</dd>

    <dt class="property-"
            title="">
        <span>Integration<wbr>Rancher</span>
        <span class="property-indicator"></span>
        <span class="property-type"><a href="#elastigroupintegrationrancher">Elastigroup<wbr>Integration<wbr>Rancher?</a></span>
    </dt>
    <dd>{{% md %}}{{% /md %}}</dd>

    <dt class="property-"
            title="">
        <span>Integration<wbr>Route53</span>
        <span class="property-indicator"></span>
        <span class="property-type"><a href="#elastigroupintegrationroute53">Elastigroup<wbr>Integration<wbr>Route53?</a></span>
    </dt>
    <dd>{{% md %}}{{% /md %}}</dd>

    <dt class="property-"
            title="">
        <span>Key<wbr>Name</span>
        <span class="property-indicator"></span>
        <span class="property-type">string?</span>
    </dt>
    <dd>{{% md %}}The key name that should be used for the instance.
{{% /md %}}</dd>

    <dt class="property-"
            title="">
        <span>Lifetime<wbr>Period</span>
        <span class="property-indicator"></span>
        <span class="property-type">string?</span>
    </dt>
    <dd>{{% md %}}{{% /md %}}</dd>

    <dt class="property-"
            title="">
        <span>Max<wbr>Size</span>
        <span class="property-indicator"></span>
        <span class="property-type">int</span>
    </dt>
    <dd>{{% md %}}The maximum number of instances the group should have at any time.
{{% /md %}}</dd>

    <dt class="property-"
            title="">
        <span>Min<wbr>Size</span>
        <span class="property-indicator"></span>
        <span class="property-type">int</span>
    </dt>
    <dd>{{% md %}}The minimum number of instances the group should have at any time.
{{% /md %}}</dd>

    <dt class="property-"
            title="">
        <span>Multai<wbr>Target<wbr>Sets</span>
        <span class="property-indicator"></span>
        <span class="property-type"><a href="#elastigroupmultaitargetset">List&lt;Elastigroup<wbr>Multai<wbr>Target<wbr>Set&gt;?</a></span>
    </dt>
    <dd>{{% md %}}{{% /md %}}</dd>

    <dt class="property-"
            title="">
        <span>Name</span>
        <span class="property-indicator"></span>
        <span class="property-type">string</span>
    </dt>
    <dd>{{% md %}}The group name.
{{% /md %}}</dd>

    <dt class="property-"
            title="">
        <span>Network<wbr>Interfaces</span>
        <span class="property-indicator"></span>
        <span class="property-type"><a href="#elastigroupnetworkinterface">List&lt;Elastigroup<wbr>Network<wbr>Interface&gt;?</a></span>
    </dt>
    <dd>{{% md %}}{{% /md %}}</dd>

    <dt class="property-"
            title="">
        <span>Ondemand<wbr>Count</span>
        <span class="property-indicator"></span>
        <span class="property-type">int?</span>
    </dt>
    <dd>{{% md %}}Number of on demand instances to launch in the group. All other instances will be spot instances. When this parameter is set the `spot_percentage` parameter is being ignored.
{{% /md %}}</dd>

    <dt class="property-"
            title="">
        <span>Orientation</span>
        <span class="property-indicator"></span>
        <span class="property-type">string</span>
    </dt>
    <dd>{{% md %}}Select a prediction strategy. Valid values: `"balanced"`, `"costOriented"`, `"equalAzDistribution"`, `"availabilityOriented"`.    
{{% /md %}}</dd>

    <dt class="property-"
            title="">
        <span>Persist<wbr>Block<wbr>Devices</span>
        <span class="property-indicator"></span>
        <span class="property-type">bool?</span>
    </dt>
    <dd>{{% md %}}{{% /md %}}</dd>

    <dt class="property-"
            title="">
        <span>Persist<wbr>Private<wbr>Ip</span>
        <span class="property-indicator"></span>
        <span class="property-type">bool?</span>
    </dt>
    <dd>{{% md %}}{{% /md %}}</dd>

    <dt class="property-"
            title="">
        <span>Persist<wbr>Root<wbr>Device</span>
        <span class="property-indicator"></span>
        <span class="property-type">bool?</span>
    </dt>
    <dd>{{% md %}}{{% /md %}}</dd>

    <dt class="property-"
            title="">
        <span>Placement<wbr>Tenancy</span>
        <span class="property-indicator"></span>
        <span class="property-type">string?</span>
    </dt>
    <dd>{{% md %}}Enable dedicated tenancy. Note: There is a flat hourly fee for each region in which dedicated tenancy is used.
{{% /md %}}</dd>

    <dt class="property-"
            title="">
        <span>Preferred<wbr>Availability<wbr>Zones</span>
        <span class="property-indicator"></span>
        <span class="property-type">List<string>?</span>
    </dt>
    <dd>{{% md %}}The AZs to prioritize when launching Spot instances. If no markets are available in the Preferred AZs, Spot instances are launched in the non-preferred AZs. 
Note: Must be a sublist of `availability_zones` and `orientation` value must not be `"equalAzDistribution"`.
{{% /md %}}</dd>

    <dt class="property-"
            title="">
        <span>Private<wbr>Ips</span>
        <span class="property-indicator"></span>
        <span class="property-type">List<string>?</span>
    </dt>
    <dd>{{% md %}}{{% /md %}}</dd>

    <dt class="property-"
            title="">
        <span>Product</span>
        <span class="property-indicator"></span>
        <span class="property-type">string</span>
    </dt>
    <dd>{{% md %}}Operation system type. Valid values: `"Linux/UNIX"`, `"SUSE Linux"`, `"Windows"`. 
For EC2 Classic instances:  `"Linux/UNIX (Amazon VPC)"`, `"SUSE Linux (Amazon VPC)"`, `"Windows (Amazon VPC)"`.
{{% /md %}}</dd>

    <dt class="property-"
            title="">
        <span>Region</span>
        <span class="property-indicator"></span>
        <span class="property-type">string?</span>
    </dt>
    <dd>{{% md %}}The AWS region your group will be created in.
Note: This parameter is required if you specify subnets (through subnet_ids). This parameter is optional if you specify Availability Zones (through availability_zones).
{{% /md %}}</dd>

    <dt class="property-"
            title="">
        <span>Revert<wbr>To<wbr>Spot</span>
        <span class="property-indicator"></span>
        <span class="property-type"><a href="#elastigroupreverttospot">Elastigroup<wbr>Revert<wbr>To<wbr>Spot?</a></span>
    </dt>
    <dd>{{% md %}}Hold settings for strategy correction – replacing On-Demand for Spot instances. Supported Values: `"never"`, `"always"`, `"timeWindow"`
{{% /md %}}</dd>

    <dt class="property-"
            title="">
        <span>Scaling<wbr>Down<wbr>Policies</span>
        <span class="property-indicator"></span>
        <span class="property-type"><a href="#elastigroupscalingdownpolicy">List&lt;Elastigroup<wbr>Scaling<wbr>Down<wbr>Policy&gt;?</a></span>
    </dt>
    <dd>{{% md %}}{{% /md %}}</dd>

    <dt class="property-"
            title="">
        <span>Scaling<wbr>Strategies</span>
        <span class="property-indicator"></span>
        <span class="property-type"><a href="#elastigroupscalingstrategy">List&lt;Elastigroup<wbr>Scaling<wbr>Strategy&gt;?</a></span>
    </dt>
    <dd>{{% md %}}Set termination policy.
{{% /md %}}</dd>

    <dt class="property-"
            title="">
        <span>Scaling<wbr>Target<wbr>Policies</span>
        <span class="property-indicator"></span>
        <span class="property-type"><a href="#elastigroupscalingtargetpolicy">List&lt;Elastigroup<wbr>Scaling<wbr>Target<wbr>Policy&gt;?</a></span>
    </dt>
    <dd>{{% md %}}{{% /md %}}</dd>

    <dt class="property-"
            title="">
        <span>Scaling<wbr>Up<wbr>Policies</span>
        <span class="property-indicator"></span>
        <span class="property-type"><a href="#elastigroupscalinguppolicy">List&lt;Elastigroup<wbr>Scaling<wbr>Up<wbr>Policy&gt;?</a></span>
    </dt>
    <dd>{{% md %}}{{% /md %}}</dd>

    <dt class="property-"
            title="">
        <span>Scheduled<wbr>Tasks</span>
        <span class="property-indicator"></span>
        <span class="property-type"><a href="#elastigroupscheduledtask">List&lt;Elastigroup<wbr>Scheduled<wbr>Task&gt;?</a></span>
    </dt>
    <dd>{{% md %}}{{% /md %}}</dd>

    <dt class="property-"
            title="">
        <span>Security<wbr>Groups</span>
        <span class="property-indicator"></span>
        <span class="property-type">List<string></span>
    </dt>
    <dd>{{% md %}}A list of associated security group IDS.
{{% /md %}}</dd>

    <dt class="property-"
            title="">
        <span>Shutdown<wbr>Script</span>
        <span class="property-indicator"></span>
        <span class="property-type">string?</span>
    </dt>
    <dd>{{% md %}}The Base64-encoded shutdown script that executes prior to instance termination, for more information please see: [Shutdown Script](https://api.spotinst.com/integration-docs/elastigroup/concepts/compute-concepts/shutdown-scripts/)
{{% /md %}}</dd>

    <dt class="property-"
            title="">
        <span>Signals</span>
        <span class="property-indicator"></span>
        <span class="property-type"><a href="#elastigroupsignal">List&lt;Elastigroup<wbr>Signal&gt;?</a></span>
    </dt>
    <dd>{{% md %}}{{% /md %}}</dd>

    <dt class="property-"
            title="">
        <span>Spot<wbr>Percentage</span>
        <span class="property-indicator"></span>
        <span class="property-type">double?</span>
    </dt>
    <dd>{{% md %}}The percentage of Spot instances that would spin up from the `desired_capacity` number.
{{% /md %}}</dd>

    <dt class="property-"
            title="">
        <span>Stateful<wbr>Deallocation</span>
        <span class="property-indicator"></span>
        <span class="property-type"><a href="#elastigroupstatefuldeallocation">Elastigroup<wbr>Stateful<wbr>Deallocation?</a></span>
    </dt>
    <dd>{{% md %}}{{% /md %}}</dd>

    <dt class="property-"
            title="">
        <span>Subnet<wbr>Ids</span>
        <span class="property-indicator"></span>
        <span class="property-type">List<string>?</span>
    </dt>
    <dd>{{% md %}}List of Strings of subnet identifiers.
Note: When this parameter is set, `availability_zones` should be left unused.
{{% /md %}}</dd>

    <dt class="property-"
            title="">
        <span>Tags</span>
        <span class="property-indicator"></span>
        <span class="property-type"><a href="#elastigrouptag">List&lt;Elastigroup<wbr>Tag&gt;?</a></span>
    </dt>
    <dd>{{% md %}}A key/value mapping of tags to assign to the resource.
{{% /md %}}</dd>

    <dt class="property-"
            title="">
        <span>Target<wbr>Group<wbr>Arns</span>
        <span class="property-indicator"></span>
        <span class="property-type">List<string>?</span>
    </dt>
    <dd>{{% md %}}{{% /md %}}</dd>

    <dt class="property-"
            title="">
        <span>Update<wbr>Policy</span>
        <span class="property-indicator"></span>
        <span class="property-type"><a href="#elastigroupupdatepolicy">Elastigroup<wbr>Update<wbr>Policy?</a></span>
    </dt>
    <dd>{{% md %}}{{% /md %}}</dd>

    <dt class="property-"
            title="">
        <span>User<wbr>Data</span>
        <span class="property-indicator"></span>
        <span class="property-type">string?</span>
    </dt>
    <dd>{{% md %}}The user data to provide when launching the instance.
{{% /md %}}</dd>

    <dt class="property-"
            title="">
        <span>Utilize<wbr>Reserved<wbr>Instances</span>
        <span class="property-indicator"></span>
        <span class="property-type">bool?</span>
    </dt>
    <dd>{{% md %}}In a case of any available reserved instances, Elastigroup will utilize them first before purchasing Spot instances.
{{% /md %}}</dd>

    <dt class="property-"
            title="">
        <span>Wait<wbr>For<wbr>Capacity</span>
        <span class="property-indicator"></span>
        <span class="property-type">int?</span>
    </dt>
    <dd>{{% md %}}Minimum number of instances in a 'HEALTHY' status that is required before continuing. This is ignored when updating with blue/green deployment. Cannot exceed `desired_capacity`.
{{% /md %}}</dd>

    <dt class="property-"
            title="">
        <span>Wait<wbr>For<wbr>Capacity<wbr>Timeout</span>
        <span class="property-indicator"></span>
        <span class="property-type">int?</span>
    </dt>
    <dd>{{% md %}}Time (seconds) to wait for instances to report a 'HEALTHY' status. Useful for plans with multiple dependencies that take some time to initialize. Leave undefined or set to `0` to indicate no wait. This is ignored when updating with blue/green deployment. 
{{% /md %}}</dd>

</dl>
{{% /choosable %}}


{{% choosable language go %}}
<dl class="resources-properties">

    <dt class="property-"
            title="">
        <span>Availability<wbr>Zones</span>
        <span class="property-indicator"></span>
        <span class="property-type">[]string</span>
    </dt>
    <dd>{{% md %}}List of Strings of availability zones. When this parameter is set, `subnet_ids` should be left unused.
Note: `availability_zones` naming syntax follows the convention `availability-zone:subnet:placement-group-name`. For example, to set an AZ in `us-east-1` with subnet `subnet-123456` and placement group `ClusterI03`, you would set:
`availability_zones = ["us-east-1a:subnet-123456:ClusterI03"]`
{{% /md %}}</dd>

    <dt class="property-"
            title="">
        <span>Block<wbr>Devices<wbr>Mode</span>
        <span class="property-indicator"></span>
        <span class="property-type">*string</span>
    </dt>
    <dd>{{% md %}}{{% /md %}}</dd>

    <dt class="property-"
            title="">
        <span>Capacity<wbr>Unit</span>
        <span class="property-indicator"></span>
        <span class="property-type">string</span>
    </dt>
    <dd>{{% md %}}The capacity unit to launch instances by. If not specified, when choosing the weight unit, each instance will weight as the number of its vCPUs.
{{% /md %}}</dd>

    <dt class="property-"
            title="">
        <span>Cpu<wbr>Credits</span>
        <span class="property-indicator"></span>
        <span class="property-type">*string</span>
    </dt>
    <dd>{{% md %}}Controls how T3 instances are launched. Valid values: `standard`, `unlimited`.
{{% /md %}}</dd>

    <dt class="property-"
            title="">
        <span>Description</span>
        <span class="property-indicator"></span>
        <span class="property-type">*string</span>
    </dt>
    <dd>{{% md %}}The group description.
{{% /md %}}</dd>

    <dt class="property-"
            title="">
        <span>Desired<wbr>Capacity</span>
        <span class="property-indicator"></span>
        <span class="property-type">*int</span>
    </dt>
    <dd>{{% md %}}The desired number of instances the group should have at any time.
{{% /md %}}</dd>

    <dt class="property-"
            title="">
        <span>Draining<wbr>Timeout</span>
        <span class="property-indicator"></span>
        <span class="property-type">int</span>
    </dt>
    <dd>{{% md %}}The time in seconds, the instance is allowed to run while detached from the ELB. This is to allow the instance time to be drained from incoming TCP connections before terminating it, during a scale down operation.
{{% /md %}}</dd>

    <dt class="property-"
            title="">
        <span>Ebs<wbr>Block<wbr>Devices</span>
        <span class="property-indicator"></span>
        <span class="property-type"><a href="#elastigroupebsblockdevice">[]Elastigroup<wbr>Ebs<wbr>Block<wbr>Device</a></span>
    </dt>
    <dd>{{% md %}}{{% /md %}}</dd>

    <dt class="property-"
            title="">
        <span>Ebs<wbr>Optimized</span>
        <span class="property-indicator"></span>
        <span class="property-type">bool</span>
    </dt>
    <dd>{{% md %}}Enable high bandwidth connectivity between instances and AWS’s Elastic Block Store (EBS). For instance types that are EBS-optimized by default this parameter will be ignored.
{{% /md %}}</dd>

    <dt class="property-"
            title="">
        <span>Elastic<wbr>Ips</span>
        <span class="property-indicator"></span>
        <span class="property-type">[]string</span>
    </dt>
    <dd>{{% md %}}A list of [AWS Elastic IP](http://docs.aws.amazon.com/AWSEC2/latest/UserGuide/elastic-ip-addresses-eip.html) allocation IDs to associate to the group instances.
{{% /md %}}</dd>

    <dt class="property-"
            title="">
        <span>Elastic<wbr>Load<wbr>Balancers</span>
        <span class="property-indicator"></span>
        <span class="property-type">[]string</span>
    </dt>
    <dd>{{% md %}}{{% /md %}}</dd>

    <dt class="property-"
            title="">
        <span>Enable<wbr>Monitoring</span>
        <span class="property-indicator"></span>
        <span class="property-type">*bool</span>
    </dt>
    <dd>{{% md %}}Indicates whether monitoring is enabled for the instance.
{{% /md %}}</dd>

    <dt class="property-"
            title="">
        <span>Ephemeral<wbr>Block<wbr>Devices</span>
        <span class="property-indicator"></span>
        <span class="property-type"><a href="#elastigroupephemeralblockdevice">[]Elastigroup<wbr>Ephemeral<wbr>Block<wbr>Device</a></span>
    </dt>
    <dd>{{% md %}}{{% /md %}}</dd>

    <dt class="property-"
            title="">
        <span>Fallback<wbr>To<wbr>Ondemand</span>
        <span class="property-indicator"></span>
        <span class="property-type">bool</span>
    </dt>
    <dd>{{% md %}}In a case of no Spot instances available, Elastigroup will launch on-demand instances instead.
{{% /md %}}</dd>

    <dt class="property-"
            title="">
        <span>Health<wbr>Check<wbr>Grace<wbr>Period</span>
        <span class="property-indicator"></span>
        <span class="property-type">*int</span>
    </dt>
    <dd>{{% md %}}The amount of time, in seconds, after the instance has launched to starts and check its health.
{{% /md %}}</dd>

    <dt class="property-"
            title="">
        <span>Health<wbr>Check<wbr>Type</span>
        <span class="property-indicator"></span>
        <span class="property-type">*string</span>
    </dt>
    <dd>{{% md %}}The service that will perform health checks for the instance. Valid values: `"ELB"`, `"HCS"`, `"TARGET_GROUP"`, `"MLB"`, `"EC2"`, `"MULTAI_TARGET_SET"`, `"MLB_RUNTIME"`, `"K8S_NODE"`, `"NOMAD_NODE"`, `"ECS_CLUSTER_INSTANCE"`.
{{% /md %}}</dd>

    <dt class="property-"
            title="">
        <span>Health<wbr>Check<wbr>Unhealthy<wbr>Duration<wbr>Before<wbr>Replacement</span>
        <span class="property-indicator"></span>
        <span class="property-type">*int</span>
    </dt>
    <dd>{{% md %}}The amount of time, in seconds, that we will wait before replacing an instance that is running and became unhealthy (this is only applicable for instances that were once healthy).
{{% /md %}}</dd>

    <dt class="property-"
            title="">
        <span>Iam<wbr>Instance<wbr>Profile</span>
        <span class="property-indicator"></span>
        <span class="property-type">*string</span>
    </dt>
    <dd>{{% md %}}The ARN or name of an IAM instance profile to associate with launched instances.
{{% /md %}}</dd>

    <dt class="property-"
            title="">
        <span>Image<wbr>Id</span>
        <span class="property-indicator"></span>
        <span class="property-type">*string</span>
    </dt>
    <dd>{{% md %}}The ID of the AMI used to launch the instance.
{{% /md %}}</dd>

    <dt class="property-"
            title="">
        <span>Instance<wbr>Types<wbr>Ondemand</span>
        <span class="property-indicator"></span>
        <span class="property-type">string</span>
    </dt>
    <dd>{{% md %}}The type of instance determines your instance's CPU capacity, memory and storage (e.g., m1.small, c1.xlarge).
{{% /md %}}</dd>

    <dt class="property-"
            title="">
        <span>Instance<wbr>Types<wbr>Preferred<wbr>Spots</span>
        <span class="property-indicator"></span>
        <span class="property-type">[]string</span>
    </dt>
    <dd>{{% md %}}Prioritize a subset of spot instance types. Must be a subset of the selected spot instance types.
{{% /md %}}</dd>

    <dt class="property-"
            title="">
        <span>Instance<wbr>Types<wbr>Spots</span>
        <span class="property-indicator"></span>
        <span class="property-type">[]string</span>
    </dt>
    <dd>{{% md %}}One or more instance types.
{{% /md %}}</dd>

    <dt class="property-"
            title="">
        <span>Instance<wbr>Types<wbr>Weights</span>
        <span class="property-indicator"></span>
        <span class="property-type"><a href="#elastigroupinstancetypesweight">[]Elastigroup<wbr>Instance<wbr>Types<wbr>Weight</a></span>
    </dt>
    <dd>{{% md %}}List of weights per instance type for weighted groups. Each object in the list should have the following attributes:
{{% /md %}}</dd>

    <dt class="property-"
            title="">
        <span>Integration<wbr>Beanstalk</span>
        <span class="property-indicator"></span>
        <span class="property-type"><a href="#elastigroupintegrationbeanstalk">*Elastigroup<wbr>Integration<wbr>Beanstalk</a></span>
    </dt>
    <dd>{{% md %}}{{% /md %}}</dd>

    <dt class="property-"
            title="">
        <span>Integration<wbr>Codedeploy</span>
        <span class="property-indicator"></span>
        <span class="property-type"><a href="#elastigroupintegrationcodedeploy">*Elastigroup<wbr>Integration<wbr>Codedeploy</a></span>
    </dt>
    <dd>{{% md %}}{{% /md %}}</dd>

    <dt class="property-"
            title="">
        <span>Integration<wbr>Docker<wbr>Swarm</span>
        <span class="property-indicator"></span>
        <span class="property-type"><a href="#elastigroupintegrationdockerswarm">*Elastigroup<wbr>Integration<wbr>Docker<wbr>Swarm</a></span>
    </dt>
    <dd>{{% md %}}{{% /md %}}</dd>

    <dt class="property-"
            title="">
        <span>Integration<wbr>Ecs</span>
        <span class="property-indicator"></span>
        <span class="property-type"><a href="#elastigroupintegrationecs">*Elastigroup<wbr>Integration<wbr>Ecs</a></span>
    </dt>
    <dd>{{% md %}}{{% /md %}}</dd>

    <dt class="property-"
            title="">
        <span>Integration<wbr>Gitlab</span>
        <span class="property-indicator"></span>
        <span class="property-type"><a href="#elastigroupintegrationgitlab">*Elastigroup<wbr>Integration<wbr>Gitlab</a></span>
    </dt>
    <dd>{{% md %}}{{% /md %}}</dd>

    <dt class="property-"
            title="">
        <span>Integration<wbr>Kubernetes</span>
        <span class="property-indicator"></span>
        <span class="property-type"><a href="#elastigroupintegrationkubernetes">*Elastigroup<wbr>Integration<wbr>Kubernetes</a></span>
    </dt>
    <dd>{{% md %}}{{% /md %}}</dd>

    <dt class="property-"
            title="">
        <span>Integration<wbr>Mesosphere</span>
        <span class="property-indicator"></span>
        <span class="property-type"><a href="#elastigroupintegrationmesosphere">*Elastigroup<wbr>Integration<wbr>Mesosphere</a></span>
    </dt>
    <dd>{{% md %}}{{% /md %}}</dd>

    <dt class="property-"
            title="">
        <span>Integration<wbr>Multai<wbr>Runtime</span>
        <span class="property-indicator"></span>
        <span class="property-type"><a href="#elastigroupintegrationmultairuntime">*Elastigroup<wbr>Integration<wbr>Multai<wbr>Runtime</a></span>
    </dt>
    <dd>{{% md %}}{{% /md %}}</dd>

    <dt class="property-"
            title="">
        <span>Integration<wbr>Nomad</span>
        <span class="property-indicator"></span>
        <span class="property-type"><a href="#elastigroupintegrationnomad">*Elastigroup<wbr>Integration<wbr>Nomad</a></span>
    </dt>
    <dd>{{% md %}}{{% /md %}}</dd>

    <dt class="property-"
            title="">
        <span>Integration<wbr>Rancher</span>
        <span class="property-indicator"></span>
        <span class="property-type"><a href="#elastigroupintegrationrancher">*Elastigroup<wbr>Integration<wbr>Rancher</a></span>
    </dt>
    <dd>{{% md %}}{{% /md %}}</dd>

    <dt class="property-"
            title="">
        <span>Integration<wbr>Route53</span>
        <span class="property-indicator"></span>
        <span class="property-type"><a href="#elastigroupintegrationroute53">*Elastigroup<wbr>Integration<wbr>Route53</a></span>
    </dt>
    <dd>{{% md %}}{{% /md %}}</dd>

    <dt class="property-"
            title="">
        <span>Key<wbr>Name</span>
        <span class="property-indicator"></span>
        <span class="property-type">*string</span>
    </dt>
    <dd>{{% md %}}The key name that should be used for the instance.
{{% /md %}}</dd>

    <dt class="property-"
            title="">
        <span>Lifetime<wbr>Period</span>
        <span class="property-indicator"></span>
        <span class="property-type">*string</span>
    </dt>
    <dd>{{% md %}}{{% /md %}}</dd>

    <dt class="property-"
            title="">
        <span>Max<wbr>Size</span>
        <span class="property-indicator"></span>
        <span class="property-type">int</span>
    </dt>
    <dd>{{% md %}}The maximum number of instances the group should have at any time.
{{% /md %}}</dd>

    <dt class="property-"
            title="">
        <span>Min<wbr>Size</span>
        <span class="property-indicator"></span>
        <span class="property-type">int</span>
    </dt>
    <dd>{{% md %}}The minimum number of instances the group should have at any time.
{{% /md %}}</dd>

    <dt class="property-"
            title="">
        <span>Multai<wbr>Target<wbr>Sets</span>
        <span class="property-indicator"></span>
        <span class="property-type"><a href="#elastigroupmultaitargetset">[]Elastigroup<wbr>Multai<wbr>Target<wbr>Set</a></span>
    </dt>
    <dd>{{% md %}}{{% /md %}}</dd>

    <dt class="property-"
            title="">
        <span>Name</span>
        <span class="property-indicator"></span>
        <span class="property-type">string</span>
    </dt>
    <dd>{{% md %}}The group name.
{{% /md %}}</dd>

    <dt class="property-"
            title="">
        <span>Network<wbr>Interfaces</span>
        <span class="property-indicator"></span>
        <span class="property-type"><a href="#elastigroupnetworkinterface">[]Elastigroup<wbr>Network<wbr>Interface</a></span>
    </dt>
    <dd>{{% md %}}{{% /md %}}</dd>

    <dt class="property-"
            title="">
        <span>Ondemand<wbr>Count</span>
        <span class="property-indicator"></span>
        <span class="property-type">*int</span>
    </dt>
    <dd>{{% md %}}Number of on demand instances to launch in the group. All other instances will be spot instances. When this parameter is set the `spot_percentage` parameter is being ignored.
{{% /md %}}</dd>

    <dt class="property-"
            title="">
        <span>Orientation</span>
        <span class="property-indicator"></span>
        <span class="property-type">string</span>
    </dt>
    <dd>{{% md %}}Select a prediction strategy. Valid values: `"balanced"`, `"costOriented"`, `"equalAzDistribution"`, `"availabilityOriented"`.    
{{% /md %}}</dd>

    <dt class="property-"
            title="">
        <span>Persist<wbr>Block<wbr>Devices</span>
        <span class="property-indicator"></span>
        <span class="property-type">*bool</span>
    </dt>
    <dd>{{% md %}}{{% /md %}}</dd>

    <dt class="property-"
            title="">
        <span>Persist<wbr>Private<wbr>Ip</span>
        <span class="property-indicator"></span>
        <span class="property-type">*bool</span>
    </dt>
    <dd>{{% md %}}{{% /md %}}</dd>

    <dt class="property-"
            title="">
        <span>Persist<wbr>Root<wbr>Device</span>
        <span class="property-indicator"></span>
        <span class="property-type">*bool</span>
    </dt>
    <dd>{{% md %}}{{% /md %}}</dd>

    <dt class="property-"
            title="">
        <span>Placement<wbr>Tenancy</span>
        <span class="property-indicator"></span>
        <span class="property-type">*string</span>
    </dt>
    <dd>{{% md %}}Enable dedicated tenancy. Note: There is a flat hourly fee for each region in which dedicated tenancy is used.
{{% /md %}}</dd>

    <dt class="property-"
            title="">
        <span>Preferred<wbr>Availability<wbr>Zones</span>
        <span class="property-indicator"></span>
        <span class="property-type">[]string</span>
    </dt>
    <dd>{{% md %}}The AZs to prioritize when launching Spot instances. If no markets are available in the Preferred AZs, Spot instances are launched in the non-preferred AZs. 
Note: Must be a sublist of `availability_zones` and `orientation` value must not be `"equalAzDistribution"`.
{{% /md %}}</dd>

    <dt class="property-"
            title="">
        <span>Private<wbr>Ips</span>
        <span class="property-indicator"></span>
        <span class="property-type">[]string</span>
    </dt>
    <dd>{{% md %}}{{% /md %}}</dd>

    <dt class="property-"
            title="">
        <span>Product</span>
        <span class="property-indicator"></span>
        <span class="property-type">string</span>
    </dt>
    <dd>{{% md %}}Operation system type. Valid values: `"Linux/UNIX"`, `"SUSE Linux"`, `"Windows"`. 
For EC2 Classic instances:  `"Linux/UNIX (Amazon VPC)"`, `"SUSE Linux (Amazon VPC)"`, `"Windows (Amazon VPC)"`.
{{% /md %}}</dd>

    <dt class="property-"
            title="">
        <span>Region</span>
        <span class="property-indicator"></span>
        <span class="property-type">*string</span>
    </dt>
    <dd>{{% md %}}The AWS region your group will be created in.
Note: This parameter is required if you specify subnets (through subnet_ids). This parameter is optional if you specify Availability Zones (through availability_zones).
{{% /md %}}</dd>

    <dt class="property-"
            title="">
        <span>Revert<wbr>To<wbr>Spot</span>
        <span class="property-indicator"></span>
        <span class="property-type"><a href="#elastigroupreverttospot">*Elastigroup<wbr>Revert<wbr>To<wbr>Spot</a></span>
    </dt>
    <dd>{{% md %}}Hold settings for strategy correction – replacing On-Demand for Spot instances. Supported Values: `"never"`, `"always"`, `"timeWindow"`
{{% /md %}}</dd>

    <dt class="property-"
            title="">
        <span>Scaling<wbr>Down<wbr>Policies</span>
        <span class="property-indicator"></span>
        <span class="property-type"><a href="#elastigroupscalingdownpolicy">[]Elastigroup<wbr>Scaling<wbr>Down<wbr>Policy</a></span>
    </dt>
    <dd>{{% md %}}{{% /md %}}</dd>

    <dt class="property-"
            title="">
        <span>Scaling<wbr>Strategies</span>
        <span class="property-indicator"></span>
        <span class="property-type"><a href="#elastigroupscalingstrategy">[]Elastigroup<wbr>Scaling<wbr>Strategy</a></span>
    </dt>
    <dd>{{% md %}}Set termination policy.
{{% /md %}}</dd>

    <dt class="property-"
            title="">
        <span>Scaling<wbr>Target<wbr>Policies</span>
        <span class="property-indicator"></span>
        <span class="property-type"><a href="#elastigroupscalingtargetpolicy">[]Elastigroup<wbr>Scaling<wbr>Target<wbr>Policy</a></span>
    </dt>
    <dd>{{% md %}}{{% /md %}}</dd>

    <dt class="property-"
            title="">
        <span>Scaling<wbr>Up<wbr>Policies</span>
        <span class="property-indicator"></span>
        <span class="property-type"><a href="#elastigroupscalinguppolicy">[]Elastigroup<wbr>Scaling<wbr>Up<wbr>Policy</a></span>
    </dt>
    <dd>{{% md %}}{{% /md %}}</dd>

    <dt class="property-"
            title="">
        <span>Scheduled<wbr>Tasks</span>
        <span class="property-indicator"></span>
        <span class="property-type"><a href="#elastigroupscheduledtask">[]Elastigroup<wbr>Scheduled<wbr>Task</a></span>
    </dt>
    <dd>{{% md %}}{{% /md %}}</dd>

    <dt class="property-"
            title="">
        <span>Security<wbr>Groups</span>
        <span class="property-indicator"></span>
        <span class="property-type">[]string</span>
    </dt>
    <dd>{{% md %}}A list of associated security group IDS.
{{% /md %}}</dd>

    <dt class="property-"
            title="">
        <span>Shutdown<wbr>Script</span>
        <span class="property-indicator"></span>
        <span class="property-type">*string</span>
    </dt>
    <dd>{{% md %}}The Base64-encoded shutdown script that executes prior to instance termination, for more information please see: [Shutdown Script](https://api.spotinst.com/integration-docs/elastigroup/concepts/compute-concepts/shutdown-scripts/)
{{% /md %}}</dd>

    <dt class="property-"
            title="">
        <span>Signals</span>
        <span class="property-indicator"></span>
        <span class="property-type"><a href="#elastigroupsignal">[]Elastigroup<wbr>Signal</a></span>
    </dt>
    <dd>{{% md %}}{{% /md %}}</dd>

    <dt class="property-"
            title="">
        <span>Spot<wbr>Percentage</span>
        <span class="property-indicator"></span>
        <span class="property-type">*float64</span>
    </dt>
    <dd>{{% md %}}The percentage of Spot instances that would spin up from the `desired_capacity` number.
{{% /md %}}</dd>

    <dt class="property-"
            title="">
        <span>Stateful<wbr>Deallocation</span>
        <span class="property-indicator"></span>
        <span class="property-type"><a href="#elastigroupstatefuldeallocation">*Elastigroup<wbr>Stateful<wbr>Deallocation</a></span>
    </dt>
    <dd>{{% md %}}{{% /md %}}</dd>

    <dt class="property-"
            title="">
        <span>Subnet<wbr>Ids</span>
        <span class="property-indicator"></span>
        <span class="property-type">[]string</span>
    </dt>
    <dd>{{% md %}}List of Strings of subnet identifiers.
Note: When this parameter is set, `availability_zones` should be left unused.
{{% /md %}}</dd>

    <dt class="property-"
            title="">
        <span>Tags</span>
        <span class="property-indicator"></span>
        <span class="property-type"><a href="#elastigrouptag">[]Elastigroup<wbr>Tag</a></span>
    </dt>
    <dd>{{% md %}}A key/value mapping of tags to assign to the resource.
{{% /md %}}</dd>

    <dt class="property-"
            title="">
        <span>Target<wbr>Group<wbr>Arns</span>
        <span class="property-indicator"></span>
        <span class="property-type">[]string</span>
    </dt>
    <dd>{{% md %}}{{% /md %}}</dd>

    <dt class="property-"
            title="">
        <span>Update<wbr>Policy</span>
        <span class="property-indicator"></span>
        <span class="property-type"><a href="#elastigroupupdatepolicy">*Elastigroup<wbr>Update<wbr>Policy</a></span>
    </dt>
    <dd>{{% md %}}{{% /md %}}</dd>

    <dt class="property-"
            title="">
        <span>User<wbr>Data</span>
        <span class="property-indicator"></span>
        <span class="property-type">*string</span>
    </dt>
    <dd>{{% md %}}The user data to provide when launching the instance.
{{% /md %}}</dd>

    <dt class="property-"
            title="">
        <span>Utilize<wbr>Reserved<wbr>Instances</span>
        <span class="property-indicator"></span>
        <span class="property-type">*bool</span>
    </dt>
    <dd>{{% md %}}In a case of any available reserved instances, Elastigroup will utilize them first before purchasing Spot instances.
{{% /md %}}</dd>

    <dt class="property-"
            title="">
        <span>Wait<wbr>For<wbr>Capacity</span>
        <span class="property-indicator"></span>
        <span class="property-type">*int</span>
    </dt>
    <dd>{{% md %}}Minimum number of instances in a 'HEALTHY' status that is required before continuing. This is ignored when updating with blue/green deployment. Cannot exceed `desired_capacity`.
{{% /md %}}</dd>

    <dt class="property-"
            title="">
        <span>Wait<wbr>For<wbr>Capacity<wbr>Timeout</span>
        <span class="property-indicator"></span>
        <span class="property-type">*int</span>
    </dt>
    <dd>{{% md %}}Time (seconds) to wait for instances to report a 'HEALTHY' status. Useful for plans with multiple dependencies that take some time to initialize. Leave undefined or set to `0` to indicate no wait. This is ignored when updating with blue/green deployment. 
{{% /md %}}</dd>

</dl>
{{% /choosable %}}


{{% choosable language nodejs %}}
<dl class="resources-properties">

    <dt class="property-"
            title="">
        <span>availability<wbr>Zones</span>
        <span class="property-indicator"></span>
        <span class="property-type">string[]?</span>
    </dt>
    <dd>{{% md %}}List of Strings of availability zones. When this parameter is set, `subnet_ids` should be left unused.
Note: `availability_zones` naming syntax follows the convention `availability-zone:subnet:placement-group-name`. For example, to set an AZ in `us-east-1` with subnet `subnet-123456` and placement group `ClusterI03`, you would set:
`availability_zones = ["us-east-1a:subnet-123456:ClusterI03"]`
{{% /md %}}</dd>

    <dt class="property-"
            title="">
        <span>block<wbr>Devices<wbr>Mode</span>
        <span class="property-indicator"></span>
        <span class="property-type">string?</span>
    </dt>
    <dd>{{% md %}}{{% /md %}}</dd>

    <dt class="property-"
            title="">
        <span>capacity<wbr>Unit</span>
        <span class="property-indicator"></span>
        <span class="property-type">string</span>
    </dt>
    <dd>{{% md %}}The capacity unit to launch instances by. If not specified, when choosing the weight unit, each instance will weight as the number of its vCPUs.
{{% /md %}}</dd>

    <dt class="property-"
            title="">
        <span>cpu<wbr>Credits</span>
        <span class="property-indicator"></span>
        <span class="property-type">string?</span>
    </dt>
    <dd>{{% md %}}Controls how T3 instances are launched. Valid values: `standard`, `unlimited`.
{{% /md %}}</dd>

    <dt class="property-"
            title="">
        <span>description</span>
        <span class="property-indicator"></span>
        <span class="property-type">string?</span>
    </dt>
    <dd>{{% md %}}The group description.
{{% /md %}}</dd>

    <dt class="property-"
            title="">
        <span>desired<wbr>Capacity</span>
        <span class="property-indicator"></span>
        <span class="property-type">number?</span>
    </dt>
    <dd>{{% md %}}The desired number of instances the group should have at any time.
{{% /md %}}</dd>

    <dt class="property-"
            title="">
        <span>draining<wbr>Timeout</span>
        <span class="property-indicator"></span>
        <span class="property-type">number</span>
    </dt>
    <dd>{{% md %}}The time in seconds, the instance is allowed to run while detached from the ELB. This is to allow the instance time to be drained from incoming TCP connections before terminating it, during a scale down operation.
{{% /md %}}</dd>

    <dt class="property-"
            title="">
        <span>ebs<wbr>Block<wbr>Devices</span>
        <span class="property-indicator"></span>
        <span class="property-type"><a href="#elastigroupebsblockdevice">Elastigroup<wbr>Ebs<wbr>Block<wbr>Device[]?</a></span>
    </dt>
    <dd>{{% md %}}{{% /md %}}</dd>

    <dt class="property-"
            title="">
        <span>ebs<wbr>Optimized</span>
        <span class="property-indicator"></span>
        <span class="property-type">boolean</span>
    </dt>
    <dd>{{% md %}}Enable high bandwidth connectivity between instances and AWS’s Elastic Block Store (EBS). For instance types that are EBS-optimized by default this parameter will be ignored.
{{% /md %}}</dd>

    <dt class="property-"
            title="">
        <span>elastic<wbr>Ips</span>
        <span class="property-indicator"></span>
        <span class="property-type">string[]?</span>
    </dt>
    <dd>{{% md %}}A list of [AWS Elastic IP](http://docs.aws.amazon.com/AWSEC2/latest/UserGuide/elastic-ip-addresses-eip.html) allocation IDs to associate to the group instances.
{{% /md %}}</dd>

    <dt class="property-"
            title="">
        <span>elastic<wbr>Load<wbr>Balancers</span>
        <span class="property-indicator"></span>
        <span class="property-type">string[]?</span>
    </dt>
    <dd>{{% md %}}{{% /md %}}</dd>

    <dt class="property-"
            title="">
        <span>enable<wbr>Monitoring</span>
        <span class="property-indicator"></span>
        <span class="property-type">boolean?</span>
    </dt>
    <dd>{{% md %}}Indicates whether monitoring is enabled for the instance.
{{% /md %}}</dd>

    <dt class="property-"
            title="">
        <span>ephemeral<wbr>Block<wbr>Devices</span>
        <span class="property-indicator"></span>
        <span class="property-type"><a href="#elastigroupephemeralblockdevice">Elastigroup<wbr>Ephemeral<wbr>Block<wbr>Device[]?</a></span>
    </dt>
    <dd>{{% md %}}{{% /md %}}</dd>

    <dt class="property-"
            title="">
        <span>fallback<wbr>To<wbr>Ondemand</span>
        <span class="property-indicator"></span>
        <span class="property-type">boolean</span>
    </dt>
    <dd>{{% md %}}In a case of no Spot instances available, Elastigroup will launch on-demand instances instead.
{{% /md %}}</dd>

    <dt class="property-"
            title="">
        <span>health<wbr>Check<wbr>Grace<wbr>Period</span>
        <span class="property-indicator"></span>
        <span class="property-type">number?</span>
    </dt>
    <dd>{{% md %}}The amount of time, in seconds, after the instance has launched to starts and check its health.
{{% /md %}}</dd>

    <dt class="property-"
            title="">
        <span>health<wbr>Check<wbr>Type</span>
        <span class="property-indicator"></span>
        <span class="property-type">string?</span>
    </dt>
    <dd>{{% md %}}The service that will perform health checks for the instance. Valid values: `"ELB"`, `"HCS"`, `"TARGET_GROUP"`, `"MLB"`, `"EC2"`, `"MULTAI_TARGET_SET"`, `"MLB_RUNTIME"`, `"K8S_NODE"`, `"NOMAD_NODE"`, `"ECS_CLUSTER_INSTANCE"`.
{{% /md %}}</dd>

    <dt class="property-"
            title="">
        <span>health<wbr>Check<wbr>Unhealthy<wbr>Duration<wbr>Before<wbr>Replacement</span>
        <span class="property-indicator"></span>
        <span class="property-type">number?</span>
    </dt>
    <dd>{{% md %}}The amount of time, in seconds, that we will wait before replacing an instance that is running and became unhealthy (this is only applicable for instances that were once healthy).
{{% /md %}}</dd>

    <dt class="property-"
            title="">
        <span>iam<wbr>Instance<wbr>Profile</span>
        <span class="property-indicator"></span>
        <span class="property-type">string?</span>
    </dt>
    <dd>{{% md %}}The ARN or name of an IAM instance profile to associate with launched instances.
{{% /md %}}</dd>

    <dt class="property-"
            title="">
        <span>image<wbr>Id</span>
        <span class="property-indicator"></span>
        <span class="property-type">string?</span>
    </dt>
    <dd>{{% md %}}The ID of the AMI used to launch the instance.
{{% /md %}}</dd>

    <dt class="property-"
            title="">
        <span>instance<wbr>Types<wbr>Ondemand</span>
        <span class="property-indicator"></span>
        <span class="property-type">string</span>
    </dt>
    <dd>{{% md %}}The type of instance determines your instance's CPU capacity, memory and storage (e.g., m1.small, c1.xlarge).
{{% /md %}}</dd>

    <dt class="property-"
            title="">
        <span>instance<wbr>Types<wbr>Preferred<wbr>Spots</span>
        <span class="property-indicator"></span>
        <span class="property-type">string[]?</span>
    </dt>
    <dd>{{% md %}}Prioritize a subset of spot instance types. Must be a subset of the selected spot instance types.
{{% /md %}}</dd>

    <dt class="property-"
            title="">
        <span>instance<wbr>Types<wbr>Spots</span>
        <span class="property-indicator"></span>
        <span class="property-type">string[]</span>
    </dt>
    <dd>{{% md %}}One or more instance types.
{{% /md %}}</dd>

    <dt class="property-"
            title="">
        <span>instance<wbr>Types<wbr>Weights</span>
        <span class="property-indicator"></span>
        <span class="property-type"><a href="#elastigroupinstancetypesweight">Elastigroup<wbr>Instance<wbr>Types<wbr>Weight[]?</a></span>
    </dt>
    <dd>{{% md %}}List of weights per instance type for weighted groups. Each object in the list should have the following attributes:
{{% /md %}}</dd>

    <dt class="property-"
            title="">
        <span>integration<wbr>Beanstalk</span>
        <span class="property-indicator"></span>
        <span class="property-type"><a href="#elastigroupintegrationbeanstalk">Elastigroup<wbr>Integration<wbr>Beanstalk?</a></span>
    </dt>
    <dd>{{% md %}}{{% /md %}}</dd>

    <dt class="property-"
            title="">
        <span>integration<wbr>Codedeploy</span>
        <span class="property-indicator"></span>
        <span class="property-type"><a href="#elastigroupintegrationcodedeploy">Elastigroup<wbr>Integration<wbr>Codedeploy?</a></span>
    </dt>
    <dd>{{% md %}}{{% /md %}}</dd>

    <dt class="property-"
            title="">
        <span>integration<wbr>Docker<wbr>Swarm</span>
        <span class="property-indicator"></span>
        <span class="property-type"><a href="#elastigroupintegrationdockerswarm">Elastigroup<wbr>Integration<wbr>Docker<wbr>Swarm?</a></span>
    </dt>
    <dd>{{% md %}}{{% /md %}}</dd>

    <dt class="property-"
            title="">
        <span>integration<wbr>Ecs</span>
        <span class="property-indicator"></span>
        <span class="property-type"><a href="#elastigroupintegrationecs">Elastigroup<wbr>Integration<wbr>Ecs?</a></span>
    </dt>
    <dd>{{% md %}}{{% /md %}}</dd>

    <dt class="property-"
            title="">
        <span>integration<wbr>Gitlab</span>
        <span class="property-indicator"></span>
        <span class="property-type"><a href="#elastigroupintegrationgitlab">Elastigroup<wbr>Integration<wbr>Gitlab?</a></span>
    </dt>
    <dd>{{% md %}}{{% /md %}}</dd>

    <dt class="property-"
            title="">
        <span>integration<wbr>Kubernetes</span>
        <span class="property-indicator"></span>
        <span class="property-type"><a href="#elastigroupintegrationkubernetes">Elastigroup<wbr>Integration<wbr>Kubernetes?</a></span>
    </dt>
    <dd>{{% md %}}{{% /md %}}</dd>

    <dt class="property-"
            title="">
        <span>integration<wbr>Mesosphere</span>
        <span class="property-indicator"></span>
        <span class="property-type"><a href="#elastigroupintegrationmesosphere">Elastigroup<wbr>Integration<wbr>Mesosphere?</a></span>
    </dt>
    <dd>{{% md %}}{{% /md %}}</dd>

    <dt class="property-"
            title="">
        <span>integration<wbr>Multai<wbr>Runtime</span>
        <span class="property-indicator"></span>
        <span class="property-type"><a href="#elastigroupintegrationmultairuntime">Elastigroup<wbr>Integration<wbr>Multai<wbr>Runtime?</a></span>
    </dt>
    <dd>{{% md %}}{{% /md %}}</dd>

    <dt class="property-"
            title="">
        <span>integration<wbr>Nomad</span>
        <span class="property-indicator"></span>
        <span class="property-type"><a href="#elastigroupintegrationnomad">Elastigroup<wbr>Integration<wbr>Nomad?</a></span>
    </dt>
    <dd>{{% md %}}{{% /md %}}</dd>

    <dt class="property-"
            title="">
        <span>integration<wbr>Rancher</span>
        <span class="property-indicator"></span>
        <span class="property-type"><a href="#elastigroupintegrationrancher">Elastigroup<wbr>Integration<wbr>Rancher?</a></span>
    </dt>
    <dd>{{% md %}}{{% /md %}}</dd>

    <dt class="property-"
            title="">
        <span>integration<wbr>Route53</span>
        <span class="property-indicator"></span>
        <span class="property-type"><a href="#elastigroupintegrationroute53">Elastigroup<wbr>Integration<wbr>Route53?</a></span>
    </dt>
    <dd>{{% md %}}{{% /md %}}</dd>

    <dt class="property-"
            title="">
        <span>key<wbr>Name</span>
        <span class="property-indicator"></span>
        <span class="property-type">string?</span>
    </dt>
    <dd>{{% md %}}The key name that should be used for the instance.
{{% /md %}}</dd>

    <dt class="property-"
            title="">
        <span>lifetime<wbr>Period</span>
        <span class="property-indicator"></span>
        <span class="property-type">string?</span>
    </dt>
    <dd>{{% md %}}{{% /md %}}</dd>

    <dt class="property-"
            title="">
        <span>max<wbr>Size</span>
        <span class="property-indicator"></span>
        <span class="property-type">number</span>
    </dt>
    <dd>{{% md %}}The maximum number of instances the group should have at any time.
{{% /md %}}</dd>

    <dt class="property-"
            title="">
        <span>min<wbr>Size</span>
        <span class="property-indicator"></span>
        <span class="property-type">number</span>
    </dt>
    <dd>{{% md %}}The minimum number of instances the group should have at any time.
{{% /md %}}</dd>

    <dt class="property-"
            title="">
        <span>multai<wbr>Target<wbr>Sets</span>
        <span class="property-indicator"></span>
        <span class="property-type"><a href="#elastigroupmultaitargetset">Elastigroup<wbr>Multai<wbr>Target<wbr>Set[]?</a></span>
    </dt>
    <dd>{{% md %}}{{% /md %}}</dd>

    <dt class="property-"
            title="">
        <span>name</span>
        <span class="property-indicator"></span>
        <span class="property-type">string</span>
    </dt>
    <dd>{{% md %}}The group name.
{{% /md %}}</dd>

    <dt class="property-"
            title="">
        <span>network<wbr>Interfaces</span>
        <span class="property-indicator"></span>
        <span class="property-type"><a href="#elastigroupnetworkinterface">Elastigroup<wbr>Network<wbr>Interface[]?</a></span>
    </dt>
    <dd>{{% md %}}{{% /md %}}</dd>

    <dt class="property-"
            title="">
        <span>ondemand<wbr>Count</span>
        <span class="property-indicator"></span>
        <span class="property-type">number?</span>
    </dt>
    <dd>{{% md %}}Number of on demand instances to launch in the group. All other instances will be spot instances. When this parameter is set the `spot_percentage` parameter is being ignored.
{{% /md %}}</dd>

    <dt class="property-"
            title="">
        <span>orientation</span>
        <span class="property-indicator"></span>
        <span class="property-type">string</span>
    </dt>
    <dd>{{% md %}}Select a prediction strategy. Valid values: `"balanced"`, `"costOriented"`, `"equalAzDistribution"`, `"availabilityOriented"`.    
{{% /md %}}</dd>

    <dt class="property-"
            title="">
        <span>persist<wbr>Block<wbr>Devices</span>
        <span class="property-indicator"></span>
        <span class="property-type">boolean?</span>
    </dt>
    <dd>{{% md %}}{{% /md %}}</dd>

    <dt class="property-"
            title="">
        <span>persist<wbr>Private<wbr>Ip</span>
        <span class="property-indicator"></span>
        <span class="property-type">boolean?</span>
    </dt>
    <dd>{{% md %}}{{% /md %}}</dd>

    <dt class="property-"
            title="">
        <span>persist<wbr>Root<wbr>Device</span>
        <span class="property-indicator"></span>
        <span class="property-type">boolean?</span>
    </dt>
    <dd>{{% md %}}{{% /md %}}</dd>

    <dt class="property-"
            title="">
        <span>placement<wbr>Tenancy</span>
        <span class="property-indicator"></span>
        <span class="property-type">string?</span>
    </dt>
    <dd>{{% md %}}Enable dedicated tenancy. Note: There is a flat hourly fee for each region in which dedicated tenancy is used.
{{% /md %}}</dd>

    <dt class="property-"
            title="">
        <span>preferred<wbr>Availability<wbr>Zones</span>
        <span class="property-indicator"></span>
        <span class="property-type">string[]?</span>
    </dt>
    <dd>{{% md %}}The AZs to prioritize when launching Spot instances. If no markets are available in the Preferred AZs, Spot instances are launched in the non-preferred AZs. 
Note: Must be a sublist of `availability_zones` and `orientation` value must not be `"equalAzDistribution"`.
{{% /md %}}</dd>

    <dt class="property-"
            title="">
        <span>private<wbr>Ips</span>
        <span class="property-indicator"></span>
        <span class="property-type">string[]?</span>
    </dt>
    <dd>{{% md %}}{{% /md %}}</dd>

    <dt class="property-"
            title="">
        <span>product</span>
        <span class="property-indicator"></span>
        <span class="property-type">string</span>
    </dt>
    <dd>{{% md %}}Operation system type. Valid values: `"Linux/UNIX"`, `"SUSE Linux"`, `"Windows"`. 
For EC2 Classic instances:  `"Linux/UNIX (Amazon VPC)"`, `"SUSE Linux (Amazon VPC)"`, `"Windows (Amazon VPC)"`.
{{% /md %}}</dd>

    <dt class="property-"
            title="">
        <span>region</span>
        <span class="property-indicator"></span>
        <span class="property-type">string?</span>
    </dt>
    <dd>{{% md %}}The AWS region your group will be created in.
Note: This parameter is required if you specify subnets (through subnet_ids). This parameter is optional if you specify Availability Zones (through availability_zones).
{{% /md %}}</dd>

    <dt class="property-"
            title="">
        <span>revert<wbr>To<wbr>Spot</span>
        <span class="property-indicator"></span>
        <span class="property-type"><a href="#elastigroupreverttospot">Elastigroup<wbr>Revert<wbr>To<wbr>Spot?</a></span>
    </dt>
    <dd>{{% md %}}Hold settings for strategy correction – replacing On-Demand for Spot instances. Supported Values: `"never"`, `"always"`, `"timeWindow"`
{{% /md %}}</dd>

    <dt class="property-"
            title="">
        <span>scaling<wbr>Down<wbr>Policies</span>
        <span class="property-indicator"></span>
        <span class="property-type"><a href="#elastigroupscalingdownpolicy">Elastigroup<wbr>Scaling<wbr>Down<wbr>Policy[]?</a></span>
    </dt>
    <dd>{{% md %}}{{% /md %}}</dd>

    <dt class="property-"
            title="">
        <span>scaling<wbr>Strategies</span>
        <span class="property-indicator"></span>
        <span class="property-type"><a href="#elastigroupscalingstrategy">Elastigroup<wbr>Scaling<wbr>Strategy[]?</a></span>
    </dt>
    <dd>{{% md %}}Set termination policy.
{{% /md %}}</dd>

    <dt class="property-"
            title="">
        <span>scaling<wbr>Target<wbr>Policies</span>
        <span class="property-indicator"></span>
        <span class="property-type"><a href="#elastigroupscalingtargetpolicy">Elastigroup<wbr>Scaling<wbr>Target<wbr>Policy[]?</a></span>
    </dt>
    <dd>{{% md %}}{{% /md %}}</dd>

    <dt class="property-"
            title="">
        <span>scaling<wbr>Up<wbr>Policies</span>
        <span class="property-indicator"></span>
        <span class="property-type"><a href="#elastigroupscalinguppolicy">Elastigroup<wbr>Scaling<wbr>Up<wbr>Policy[]?</a></span>
    </dt>
    <dd>{{% md %}}{{% /md %}}</dd>

    <dt class="property-"
            title="">
        <span>scheduled<wbr>Tasks</span>
        <span class="property-indicator"></span>
        <span class="property-type"><a href="#elastigroupscheduledtask">Elastigroup<wbr>Scheduled<wbr>Task[]?</a></span>
    </dt>
    <dd>{{% md %}}{{% /md %}}</dd>

    <dt class="property-"
            title="">
        <span>security<wbr>Groups</span>
        <span class="property-indicator"></span>
        <span class="property-type">string[]</span>
    </dt>
    <dd>{{% md %}}A list of associated security group IDS.
{{% /md %}}</dd>

    <dt class="property-"
            title="">
        <span>shutdown<wbr>Script</span>
        <span class="property-indicator"></span>
        <span class="property-type">string?</span>
    </dt>
    <dd>{{% md %}}The Base64-encoded shutdown script that executes prior to instance termination, for more information please see: [Shutdown Script](https://api.spotinst.com/integration-docs/elastigroup/concepts/compute-concepts/shutdown-scripts/)
{{% /md %}}</dd>

    <dt class="property-"
            title="">
        <span>signals</span>
        <span class="property-indicator"></span>
        <span class="property-type"><a href="#elastigroupsignal">Elastigroup<wbr>Signal[]?</a></span>
    </dt>
    <dd>{{% md %}}{{% /md %}}</dd>

    <dt class="property-"
            title="">
        <span>spot<wbr>Percentage</span>
        <span class="property-indicator"></span>
        <span class="property-type">number?</span>
    </dt>
    <dd>{{% md %}}The percentage of Spot instances that would spin up from the `desired_capacity` number.
{{% /md %}}</dd>

    <dt class="property-"
            title="">
        <span>stateful<wbr>Deallocation</span>
        <span class="property-indicator"></span>
        <span class="property-type"><a href="#elastigroupstatefuldeallocation">Elastigroup<wbr>Stateful<wbr>Deallocation?</a></span>
    </dt>
    <dd>{{% md %}}{{% /md %}}</dd>

    <dt class="property-"
            title="">
        <span>subnet<wbr>Ids</span>
        <span class="property-indicator"></span>
        <span class="property-type">string[]?</span>
    </dt>
    <dd>{{% md %}}List of Strings of subnet identifiers.
Note: When this parameter is set, `availability_zones` should be left unused.
{{% /md %}}</dd>

    <dt class="property-"
            title="">
        <span>tags</span>
        <span class="property-indicator"></span>
        <span class="property-type"><a href="#elastigrouptag">Elastigroup<wbr>Tag[]?</a></span>
    </dt>
    <dd>{{% md %}}A key/value mapping of tags to assign to the resource.
{{% /md %}}</dd>

    <dt class="property-"
            title="">
        <span>target<wbr>Group<wbr>Arns</span>
        <span class="property-indicator"></span>
        <span class="property-type">string[]?</span>
    </dt>
    <dd>{{% md %}}{{% /md %}}</dd>

    <dt class="property-"
            title="">
        <span>update<wbr>Policy</span>
        <span class="property-indicator"></span>
        <span class="property-type"><a href="#elastigroupupdatepolicy">Elastigroup<wbr>Update<wbr>Policy?</a></span>
    </dt>
    <dd>{{% md %}}{{% /md %}}</dd>

    <dt class="property-"
            title="">
        <span>user<wbr>Data</span>
        <span class="property-indicator"></span>
        <span class="property-type">string?</span>
    </dt>
    <dd>{{% md %}}The user data to provide when launching the instance.
{{% /md %}}</dd>

    <dt class="property-"
            title="">
        <span>utilize<wbr>Reserved<wbr>Instances</span>
        <span class="property-indicator"></span>
        <span class="property-type">boolean?</span>
    </dt>
    <dd>{{% md %}}In a case of any available reserved instances, Elastigroup will utilize them first before purchasing Spot instances.
{{% /md %}}</dd>

    <dt class="property-"
            title="">
        <span>wait<wbr>For<wbr>Capacity</span>
        <span class="property-indicator"></span>
        <span class="property-type">number?</span>
    </dt>
    <dd>{{% md %}}Minimum number of instances in a 'HEALTHY' status that is required before continuing. This is ignored when updating with blue/green deployment. Cannot exceed `desired_capacity`.
{{% /md %}}</dd>

    <dt class="property-"
            title="">
        <span>wait<wbr>For<wbr>Capacity<wbr>Timeout</span>
        <span class="property-indicator"></span>
        <span class="property-type">number?</span>
    </dt>
    <dd>{{% md %}}Time (seconds) to wait for instances to report a 'HEALTHY' status. Useful for plans with multiple dependencies that take some time to initialize. Leave undefined or set to `0` to indicate no wait. This is ignored when updating with blue/green deployment. 
{{% /md %}}</dd>

</dl>
{{% /choosable %}}


{{% choosable language python %}}
<dl class="resources-properties">

    <dt class="property-"
            title="">
        <span>availability_<wbr>zones</span>
        <span class="property-indicator"></span>
        <span class="property-type">List[str]</span>
    </dt>
    <dd>{{% md %}}List of Strings of availability zones. When this parameter is set, `subnet_ids` should be left unused.
Note: `availability_zones` naming syntax follows the convention `availability-zone:subnet:placement-group-name`. For example, to set an AZ in `us-east-1` with subnet `subnet-123456` and placement group `ClusterI03`, you would set:
`availability_zones = ["us-east-1a:subnet-123456:ClusterI03"]`
{{% /md %}}</dd>

    <dt class="property-"
            title="">
        <span>block_<wbr>devices_<wbr>mode</span>
        <span class="property-indicator"></span>
        <span class="property-type">str</span>
    </dt>
    <dd>{{% md %}}{{% /md %}}</dd>

    <dt class="property-"
            title="">
        <span>capacity_<wbr>unit</span>
        <span class="property-indicator"></span>
        <span class="property-type">str</span>
    </dt>
    <dd>{{% md %}}The capacity unit to launch instances by. If not specified, when choosing the weight unit, each instance will weight as the number of its vCPUs.
{{% /md %}}</dd>

    <dt class="property-"
            title="">
        <span>cpu_<wbr>credits</span>
        <span class="property-indicator"></span>
        <span class="property-type">str</span>
    </dt>
    <dd>{{% md %}}Controls how T3 instances are launched. Valid values: `standard`, `unlimited`.
{{% /md %}}</dd>

    <dt class="property-"
            title="">
        <span>description</span>
        <span class="property-indicator"></span>
        <span class="property-type">str</span>
    </dt>
    <dd>{{% md %}}The group description.
{{% /md %}}</dd>

    <dt class="property-"
            title="">
        <span>desired_<wbr>capacity</span>
        <span class="property-indicator"></span>
        <span class="property-type">float</span>
    </dt>
    <dd>{{% md %}}The desired number of instances the group should have at any time.
{{% /md %}}</dd>

    <dt class="property-"
            title="">
        <span>draining_<wbr>timeout</span>
        <span class="property-indicator"></span>
        <span class="property-type">float</span>
    </dt>
    <dd>{{% md %}}The time in seconds, the instance is allowed to run while detached from the ELB. This is to allow the instance time to be drained from incoming TCP connections before terminating it, during a scale down operation.
{{% /md %}}</dd>

    <dt class="property-"
            title="">
        <span>ebs_<wbr>block_<wbr>devices</span>
        <span class="property-indicator"></span>
        <span class="property-type"><a href="#elastigroupebsblockdevice">List[Elastigroup<wbr>Ebs<wbr>Block<wbr>Device]</a></span>
    </dt>
    <dd>{{% md %}}{{% /md %}}</dd>

    <dt class="property-"
            title="">
        <span>ebs_<wbr>optimized</span>
        <span class="property-indicator"></span>
        <span class="property-type">bool</span>
    </dt>
    <dd>{{% md %}}Enable high bandwidth connectivity between instances and AWS’s Elastic Block Store (EBS). For instance types that are EBS-optimized by default this parameter will be ignored.
{{% /md %}}</dd>

    <dt class="property-"
            title="">
        <span>elastic_<wbr>ips</span>
        <span class="property-indicator"></span>
        <span class="property-type">List[str]</span>
    </dt>
    <dd>{{% md %}}A list of [AWS Elastic IP](http://docs.aws.amazon.com/AWSEC2/latest/UserGuide/elastic-ip-addresses-eip.html) allocation IDs to associate to the group instances.
{{% /md %}}</dd>

    <dt class="property-"
            title="">
        <span>elastic_<wbr>load_<wbr>balancers</span>
        <span class="property-indicator"></span>
        <span class="property-type">List[str]</span>
    </dt>
    <dd>{{% md %}}{{% /md %}}</dd>

    <dt class="property-"
            title="">
        <span>enable_<wbr>monitoring</span>
        <span class="property-indicator"></span>
        <span class="property-type">bool</span>
    </dt>
    <dd>{{% md %}}Indicates whether monitoring is enabled for the instance.
{{% /md %}}</dd>

    <dt class="property-"
            title="">
        <span>ephemeral_<wbr>block_<wbr>devices</span>
        <span class="property-indicator"></span>
        <span class="property-type"><a href="#elastigroupephemeralblockdevice">List[Elastigroup<wbr>Ephemeral<wbr>Block<wbr>Device]</a></span>
    </dt>
    <dd>{{% md %}}{{% /md %}}</dd>

    <dt class="property-"
            title="">
        <span>fallback_<wbr>to_<wbr>ondemand</span>
        <span class="property-indicator"></span>
        <span class="property-type">bool</span>
    </dt>
    <dd>{{% md %}}In a case of no Spot instances available, Elastigroup will launch on-demand instances instead.
{{% /md %}}</dd>

    <dt class="property-"
            title="">
        <span>health_<wbr>check_<wbr>grace_<wbr>period</span>
        <span class="property-indicator"></span>
        <span class="property-type">float</span>
    </dt>
    <dd>{{% md %}}The amount of time, in seconds, after the instance has launched to starts and check its health.
{{% /md %}}</dd>

    <dt class="property-"
            title="">
        <span>health_<wbr>check_<wbr>type</span>
        <span class="property-indicator"></span>
        <span class="property-type">str</span>
    </dt>
    <dd>{{% md %}}The service that will perform health checks for the instance. Valid values: `"ELB"`, `"HCS"`, `"TARGET_GROUP"`, `"MLB"`, `"EC2"`, `"MULTAI_TARGET_SET"`, `"MLB_RUNTIME"`, `"K8S_NODE"`, `"NOMAD_NODE"`, `"ECS_CLUSTER_INSTANCE"`.
{{% /md %}}</dd>

    <dt class="property-"
            title="">
        <span>health_<wbr>check_<wbr>unhealthy_<wbr>duration_<wbr>before_<wbr>replacement</span>
        <span class="property-indicator"></span>
        <span class="property-type">float</span>
    </dt>
    <dd>{{% md %}}The amount of time, in seconds, that we will wait before replacing an instance that is running and became unhealthy (this is only applicable for instances that were once healthy).
{{% /md %}}</dd>

    <dt class="property-"
            title="">
        <span>iam_<wbr>instance_<wbr>profile</span>
        <span class="property-indicator"></span>
        <span class="property-type">str</span>
    </dt>
    <dd>{{% md %}}The ARN or name of an IAM instance profile to associate with launched instances.
{{% /md %}}</dd>

    <dt class="property-"
            title="">
        <span>image_<wbr>id</span>
        <span class="property-indicator"></span>
        <span class="property-type">str</span>
    </dt>
    <dd>{{% md %}}The ID of the AMI used to launch the instance.
{{% /md %}}</dd>

    <dt class="property-"
            title="">
        <span>instance_<wbr>types_<wbr>ondemand</span>
        <span class="property-indicator"></span>
        <span class="property-type">str</span>
    </dt>
    <dd>{{% md %}}The type of instance determines your instance's CPU capacity, memory and storage (e.g., m1.small, c1.xlarge).
{{% /md %}}</dd>

    <dt class="property-"
            title="">
        <span>instance_<wbr>types_<wbr>preferred_<wbr>spots</span>
        <span class="property-indicator"></span>
        <span class="property-type">List[str]</span>
    </dt>
    <dd>{{% md %}}Prioritize a subset of spot instance types. Must be a subset of the selected spot instance types.
{{% /md %}}</dd>

    <dt class="property-"
            title="">
        <span>instance_<wbr>types_<wbr>spots</span>
        <span class="property-indicator"></span>
        <span class="property-type">List[str]</span>
    </dt>
    <dd>{{% md %}}One or more instance types.
{{% /md %}}</dd>

    <dt class="property-"
            title="">
        <span>instance_<wbr>types_<wbr>weights</span>
        <span class="property-indicator"></span>
        <span class="property-type"><a href="#elastigroupinstancetypesweight">List[Elastigroup<wbr>Instance<wbr>Types<wbr>Weight]</a></span>
    </dt>
    <dd>{{% md %}}List of weights per instance type for weighted groups. Each object in the list should have the following attributes:
{{% /md %}}</dd>

    <dt class="property-"
            title="">
        <span>integration_<wbr>beanstalk</span>
        <span class="property-indicator"></span>
        <span class="property-type"><a href="#elastigroupintegrationbeanstalk">Dict[Elastigroup<wbr>Integration<wbr>Beanstalk]</a></span>
    </dt>
    <dd>{{% md %}}{{% /md %}}</dd>

    <dt class="property-"
            title="">
        <span>integration_<wbr>codedeploy</span>
        <span class="property-indicator"></span>
        <span class="property-type"><a href="#elastigroupintegrationcodedeploy">Dict[Elastigroup<wbr>Integration<wbr>Codedeploy]</a></span>
    </dt>
    <dd>{{% md %}}{{% /md %}}</dd>

    <dt class="property-"
            title="">
        <span>integration_<wbr>docker_<wbr>swarm</span>
        <span class="property-indicator"></span>
        <span class="property-type"><a href="#elastigroupintegrationdockerswarm">Dict[Elastigroup<wbr>Integration<wbr>Docker<wbr>Swarm]</a></span>
    </dt>
    <dd>{{% md %}}{{% /md %}}</dd>

    <dt class="property-"
            title="">
        <span>integration_<wbr>ecs</span>
        <span class="property-indicator"></span>
        <span class="property-type"><a href="#elastigroupintegrationecs">Dict[Elastigroup<wbr>Integration<wbr>Ecs]</a></span>
    </dt>
    <dd>{{% md %}}{{% /md %}}</dd>

    <dt class="property-"
            title="">
        <span>integration_<wbr>gitlab</span>
        <span class="property-indicator"></span>
        <span class="property-type"><a href="#elastigroupintegrationgitlab">Dict[Elastigroup<wbr>Integration<wbr>Gitlab]</a></span>
    </dt>
    <dd>{{% md %}}{{% /md %}}</dd>

    <dt class="property-"
            title="">
        <span>integration_<wbr>kubernetes</span>
        <span class="property-indicator"></span>
        <span class="property-type"><a href="#elastigroupintegrationkubernetes">Dict[Elastigroup<wbr>Integration<wbr>Kubernetes]</a></span>
    </dt>
    <dd>{{% md %}}{{% /md %}}</dd>

    <dt class="property-"
            title="">
        <span>integration_<wbr>mesosphere</span>
        <span class="property-indicator"></span>
        <span class="property-type"><a href="#elastigroupintegrationmesosphere">Dict[Elastigroup<wbr>Integration<wbr>Mesosphere]</a></span>
    </dt>
    <dd>{{% md %}}{{% /md %}}</dd>

    <dt class="property-"
            title="">
        <span>integration_<wbr>multai_<wbr>runtime</span>
        <span class="property-indicator"></span>
        <span class="property-type"><a href="#elastigroupintegrationmultairuntime">Dict[Elastigroup<wbr>Integration<wbr>Multai<wbr>Runtime]</a></span>
    </dt>
    <dd>{{% md %}}{{% /md %}}</dd>

    <dt class="property-"
            title="">
        <span>integration_<wbr>nomad</span>
        <span class="property-indicator"></span>
        <span class="property-type"><a href="#elastigroupintegrationnomad">Dict[Elastigroup<wbr>Integration<wbr>Nomad]</a></span>
    </dt>
    <dd>{{% md %}}{{% /md %}}</dd>

    <dt class="property-"
            title="">
        <span>integration_<wbr>rancher</span>
        <span class="property-indicator"></span>
        <span class="property-type"><a href="#elastigroupintegrationrancher">Dict[Elastigroup<wbr>Integration<wbr>Rancher]</a></span>
    </dt>
    <dd>{{% md %}}{{% /md %}}</dd>

    <dt class="property-"
            title="">
        <span>integration_<wbr>route53</span>
        <span class="property-indicator"></span>
        <span class="property-type"><a href="#elastigroupintegrationroute53">Dict[Elastigroup<wbr>Integration<wbr>Route53]</a></span>
    </dt>
    <dd>{{% md %}}{{% /md %}}</dd>

    <dt class="property-"
            title="">
        <span>key_<wbr>name</span>
        <span class="property-indicator"></span>
        <span class="property-type">str</span>
    </dt>
    <dd>{{% md %}}The key name that should be used for the instance.
{{% /md %}}</dd>

    <dt class="property-"
            title="">
        <span>lifetime_<wbr>period</span>
        <span class="property-indicator"></span>
        <span class="property-type">str</span>
    </dt>
    <dd>{{% md %}}{{% /md %}}</dd>

    <dt class="property-"
            title="">
        <span>max_<wbr>size</span>
        <span class="property-indicator"></span>
        <span class="property-type">float</span>
    </dt>
    <dd>{{% md %}}The maximum number of instances the group should have at any time.
{{% /md %}}</dd>

    <dt class="property-"
            title="">
        <span>min_<wbr>size</span>
        <span class="property-indicator"></span>
        <span class="property-type">float</span>
    </dt>
    <dd>{{% md %}}The minimum number of instances the group should have at any time.
{{% /md %}}</dd>

    <dt class="property-"
            title="">
        <span>multai_<wbr>target_<wbr>sets</span>
        <span class="property-indicator"></span>
        <span class="property-type"><a href="#elastigroupmultaitargetset">List[Elastigroup<wbr>Multai<wbr>Target<wbr>Set]</a></span>
    </dt>
    <dd>{{% md %}}{{% /md %}}</dd>

    <dt class="property-"
            title="">
        <span>name</span>
        <span class="property-indicator"></span>
        <span class="property-type">str</span>
    </dt>
    <dd>{{% md %}}The group name.
{{% /md %}}</dd>

    <dt class="property-"
            title="">
        <span>network_<wbr>interfaces</span>
        <span class="property-indicator"></span>
        <span class="property-type"><a href="#elastigroupnetworkinterface">List[Elastigroup<wbr>Network<wbr>Interface]</a></span>
    </dt>
    <dd>{{% md %}}{{% /md %}}</dd>

    <dt class="property-"
            title="">
        <span>ondemand_<wbr>count</span>
        <span class="property-indicator"></span>
        <span class="property-type">float</span>
    </dt>
    <dd>{{% md %}}Number of on demand instances to launch in the group. All other instances will be spot instances. When this parameter is set the `spot_percentage` parameter is being ignored.
{{% /md %}}</dd>

    <dt class="property-"
            title="">
        <span>orientation</span>
        <span class="property-indicator"></span>
        <span class="property-type">str</span>
    </dt>
    <dd>{{% md %}}Select a prediction strategy. Valid values: `"balanced"`, `"costOriented"`, `"equalAzDistribution"`, `"availabilityOriented"`.    
{{% /md %}}</dd>

    <dt class="property-"
            title="">
        <span>persist_<wbr>block_<wbr>devices</span>
        <span class="property-indicator"></span>
        <span class="property-type">bool</span>
    </dt>
    <dd>{{% md %}}{{% /md %}}</dd>

    <dt class="property-"
            title="">
        <span>persist_<wbr>private_<wbr>ip</span>
        <span class="property-indicator"></span>
        <span class="property-type">bool</span>
    </dt>
    <dd>{{% md %}}{{% /md %}}</dd>

    <dt class="property-"
            title="">
        <span>persist_<wbr>root_<wbr>device</span>
        <span class="property-indicator"></span>
        <span class="property-type">bool</span>
    </dt>
    <dd>{{% md %}}{{% /md %}}</dd>

    <dt class="property-"
            title="">
        <span>placement_<wbr>tenancy</span>
        <span class="property-indicator"></span>
        <span class="property-type">str</span>
    </dt>
    <dd>{{% md %}}Enable dedicated tenancy. Note: There is a flat hourly fee for each region in which dedicated tenancy is used.
{{% /md %}}</dd>

    <dt class="property-"
            title="">
        <span>preferred_<wbr>availability_<wbr>zones</span>
        <span class="property-indicator"></span>
        <span class="property-type">List[str]</span>
    </dt>
    <dd>{{% md %}}The AZs to prioritize when launching Spot instances. If no markets are available in the Preferred AZs, Spot instances are launched in the non-preferred AZs. 
Note: Must be a sublist of `availability_zones` and `orientation` value must not be `"equalAzDistribution"`.
{{% /md %}}</dd>

    <dt class="property-"
            title="">
        <span>private_<wbr>ips</span>
        <span class="property-indicator"></span>
        <span class="property-type">List[str]</span>
    </dt>
    <dd>{{% md %}}{{% /md %}}</dd>

    <dt class="property-"
            title="">
        <span>product</span>
        <span class="property-indicator"></span>
        <span class="property-type">str</span>
    </dt>
    <dd>{{% md %}}Operation system type. Valid values: `"Linux/UNIX"`, `"SUSE Linux"`, `"Windows"`. 
For EC2 Classic instances:  `"Linux/UNIX (Amazon VPC)"`, `"SUSE Linux (Amazon VPC)"`, `"Windows (Amazon VPC)"`.
{{% /md %}}</dd>

    <dt class="property-"
            title="">
        <span>region</span>
        <span class="property-indicator"></span>
        <span class="property-type">str</span>
    </dt>
    <dd>{{% md %}}The AWS region your group will be created in.
Note: This parameter is required if you specify subnets (through subnet_ids). This parameter is optional if you specify Availability Zones (through availability_zones).
{{% /md %}}</dd>

    <dt class="property-"
            title="">
        <span>revert_<wbr>to_<wbr>spot</span>
        <span class="property-indicator"></span>
        <span class="property-type"><a href="#elastigroupreverttospot">Dict[Elastigroup<wbr>Revert<wbr>To<wbr>Spot]</a></span>
    </dt>
    <dd>{{% md %}}Hold settings for strategy correction – replacing On-Demand for Spot instances. Supported Values: `"never"`, `"always"`, `"timeWindow"`
{{% /md %}}</dd>

    <dt class="property-"
            title="">
        <span>scaling_<wbr>down_<wbr>policies</span>
        <span class="property-indicator"></span>
        <span class="property-type"><a href="#elastigroupscalingdownpolicy">List[Elastigroup<wbr>Scaling<wbr>Down<wbr>Policy]</a></span>
    </dt>
    <dd>{{% md %}}{{% /md %}}</dd>

    <dt class="property-"
            title="">
        <span>scaling_<wbr>strategies</span>
        <span class="property-indicator"></span>
        <span class="property-type"><a href="#elastigroupscalingstrategy">List[Elastigroup<wbr>Scaling<wbr>Strategy]</a></span>
    </dt>
    <dd>{{% md %}}Set termination policy.
{{% /md %}}</dd>

    <dt class="property-"
            title="">
        <span>scaling_<wbr>target_<wbr>policies</span>
        <span class="property-indicator"></span>
        <span class="property-type"><a href="#elastigroupscalingtargetpolicy">List[Elastigroup<wbr>Scaling<wbr>Target<wbr>Policy]</a></span>
    </dt>
    <dd>{{% md %}}{{% /md %}}</dd>

    <dt class="property-"
            title="">
        <span>scaling_<wbr>up_<wbr>policies</span>
        <span class="property-indicator"></span>
        <span class="property-type"><a href="#elastigroupscalinguppolicy">List[Elastigroup<wbr>Scaling<wbr>Up<wbr>Policy]</a></span>
    </dt>
    <dd>{{% md %}}{{% /md %}}</dd>

    <dt class="property-"
            title="">
        <span>scheduled_<wbr>tasks</span>
        <span class="property-indicator"></span>
        <span class="property-type"><a href="#elastigroupscheduledtask">List[Elastigroup<wbr>Scheduled<wbr>Task]</a></span>
    </dt>
    <dd>{{% md %}}{{% /md %}}</dd>

    <dt class="property-"
            title="">
        <span>security_<wbr>groups</span>
        <span class="property-indicator"></span>
        <span class="property-type">List[str]</span>
    </dt>
    <dd>{{% md %}}A list of associated security group IDS.
{{% /md %}}</dd>

    <dt class="property-"
            title="">
        <span>shutdown_<wbr>script</span>
        <span class="property-indicator"></span>
        <span class="property-type">str</span>
    </dt>
    <dd>{{% md %}}The Base64-encoded shutdown script that executes prior to instance termination, for more information please see: [Shutdown Script](https://api.spotinst.com/integration-docs/elastigroup/concepts/compute-concepts/shutdown-scripts/)
{{% /md %}}</dd>

    <dt class="property-"
            title="">
        <span>signals</span>
        <span class="property-indicator"></span>
        <span class="property-type"><a href="#elastigroupsignal">List[Elastigroup<wbr>Signal]</a></span>
    </dt>
    <dd>{{% md %}}{{% /md %}}</dd>

    <dt class="property-"
            title="">
        <span>spot_<wbr>percentage</span>
        <span class="property-indicator"></span>
        <span class="property-type">float</span>
    </dt>
    <dd>{{% md %}}The percentage of Spot instances that would spin up from the `desired_capacity` number.
{{% /md %}}</dd>

    <dt class="property-"
            title="">
        <span>stateful_<wbr>deallocation</span>
        <span class="property-indicator"></span>
        <span class="property-type"><a href="#elastigroupstatefuldeallocation">Dict[Elastigroup<wbr>Stateful<wbr>Deallocation]</a></span>
    </dt>
    <dd>{{% md %}}{{% /md %}}</dd>

    <dt class="property-"
            title="">
        <span>subnet_<wbr>ids</span>
        <span class="property-indicator"></span>
        <span class="property-type">List[str]</span>
    </dt>
    <dd>{{% md %}}List of Strings of subnet identifiers.
Note: When this parameter is set, `availability_zones` should be left unused.
{{% /md %}}</dd>

    <dt class="property-"
            title="">
        <span>tags</span>
        <span class="property-indicator"></span>
        <span class="property-type"><a href="#elastigrouptag">List[Elastigroup<wbr>Tag]</a></span>
    </dt>
    <dd>{{% md %}}A key/value mapping of tags to assign to the resource.
{{% /md %}}</dd>

    <dt class="property-"
            title="">
        <span>target_<wbr>group_<wbr>arns</span>
        <span class="property-indicator"></span>
        <span class="property-type">List[str]</span>
    </dt>
    <dd>{{% md %}}{{% /md %}}</dd>

    <dt class="property-"
            title="">
        <span>update_<wbr>policy</span>
        <span class="property-indicator"></span>
        <span class="property-type"><a href="#elastigroupupdatepolicy">Dict[Elastigroup<wbr>Update<wbr>Policy]</a></span>
    </dt>
    <dd>{{% md %}}{{% /md %}}</dd>

    <dt class="property-"
            title="">
        <span>user_<wbr>data</span>
        <span class="property-indicator"></span>
        <span class="property-type">str</span>
    </dt>
    <dd>{{% md %}}The user data to provide when launching the instance.
{{% /md %}}</dd>

    <dt class="property-"
            title="">
        <span>utilize_<wbr>reserved_<wbr>instances</span>
        <span class="property-indicator"></span>
        <span class="property-type">bool</span>
    </dt>
    <dd>{{% md %}}In a case of any available reserved instances, Elastigroup will utilize them first before purchasing Spot instances.
{{% /md %}}</dd>

    <dt class="property-"
            title="">
        <span>wait_<wbr>for_<wbr>capacity</span>
        <span class="property-indicator"></span>
        <span class="property-type">float</span>
    </dt>
    <dd>{{% md %}}Minimum number of instances in a 'HEALTHY' status that is required before continuing. This is ignored when updating with blue/green deployment. Cannot exceed `desired_capacity`.
{{% /md %}}</dd>

    <dt class="property-"
            title="">
        <span>wait_<wbr>for_<wbr>capacity_<wbr>timeout</span>
        <span class="property-indicator"></span>
        <span class="property-type">float</span>
    </dt>
    <dd>{{% md %}}Time (seconds) to wait for instances to report a 'HEALTHY' status. Useful for plans with multiple dependencies that take some time to initialize. Leave undefined or set to `0` to indicate no wait. This is ignored when updating with blue/green deployment. 
{{% /md %}}</dd>

</dl>
{{% /choosable %}}








## Look up an Existing Elastigroup Resource

Get an existing Elastigroup resource's state with the given name, ID, and optional extra properties used to qualify the lookup.

{{< chooser language "javascript,typescript,python,go,csharp  " / >}}

{{% choosable language nodejs %}}
<div class="highlight"><pre class="chroma"><code class="language-typescript" data-lang="typescript"><span class="k">public static </span><span class="nf">get</span><span class="p">(</span><span class="nx">name</span>: <span class="nx"><a href="https://developer.mozilla.org/en-US/docs/Web/JavaScript/Reference/Global_Objects/string">string</a></span><span class="p">, </span><span class="nx">id</span>: <span class="nx"><a href="/docs/reference/pkg/nodejs/pulumi/pulumi/#ID">Input&lt;ID&gt;</a></span><span class="p">, </span><span class="nx">state</span>?: <span class="nx"><a href="/docs/reference/pkg/nodejs/pulumi/spotinst/aws/#ElastigroupState">ElastigroupState</a></span><span class="p">, </span><span class="nx">opts</span>?: <span class="nx"><a href="/docs/reference/pkg/nodejs/pulumi/pulumi/#CustomResourceOptions">CustomResourceOptions</a></span><span class="p">): </span><span class="nx"><a href="/docs/reference/pkg/nodejs/pulumi/spotinst/aws/#Elastigroup">Elastigroup</a></span></code></pre></div>
{{% /choosable %}}

{{% choosable language python %}}
<div class="highlight"><pre class="chroma"><code class="language-python" data-lang="python"><span class="k">static </span><span class="nf">get</span><span class="p">(resource_name, id, opts=None, </span>availability_zones=None<span class="p">, </span>block_devices_mode=None<span class="p">, </span>capacity_unit=None<span class="p">, </span>cpu_credits=None<span class="p">, </span>description=None<span class="p">, </span>desired_capacity=None<span class="p">, </span>draining_timeout=None<span class="p">, </span>ebs_block_devices=None<span class="p">, </span>ebs_optimized=None<span class="p">, </span>elastic_ips=None<span class="p">, </span>elastic_load_balancers=None<span class="p">, </span>enable_monitoring=None<span class="p">, </span>ephemeral_block_devices=None<span class="p">, </span>fallback_to_ondemand=None<span class="p">, </span>health_check_grace_period=None<span class="p">, </span>health_check_type=None<span class="p">, </span>health_check_unhealthy_duration_before_replacement=None<span class="p">, </span>iam_instance_profile=None<span class="p">, </span>image_id=None<span class="p">, </span>instance_types_ondemand=None<span class="p">, </span>instance_types_preferred_spots=None<span class="p">, </span>instance_types_spots=None<span class="p">, </span>instance_types_weights=None<span class="p">, </span>integration_beanstalk=None<span class="p">, </span>integration_codedeploy=None<span class="p">, </span>integration_docker_swarm=None<span class="p">, </span>integration_ecs=None<span class="p">, </span>integration_gitlab=None<span class="p">, </span>integration_kubernetes=None<span class="p">, </span>integration_mesosphere=None<span class="p">, </span>integration_multai_runtime=None<span class="p">, </span>integration_nomad=None<span class="p">, </span>integration_rancher=None<span class="p">, </span>integration_route53=None<span class="p">, </span>key_name=None<span class="p">, </span>lifetime_period=None<span class="p">, </span>max_size=None<span class="p">, </span>min_size=None<span class="p">, </span>multai_target_sets=None<span class="p">, </span>name=None<span class="p">, </span>network_interfaces=None<span class="p">, </span>ondemand_count=None<span class="p">, </span>orientation=None<span class="p">, </span>persist_block_devices=None<span class="p">, </span>persist_private_ip=None<span class="p">, </span>persist_root_device=None<span class="p">, </span>placement_tenancy=None<span class="p">, </span>preferred_availability_zones=None<span class="p">, </span>private_ips=None<span class="p">, </span>product=None<span class="p">, </span>region=None<span class="p">, </span>revert_to_spot=None<span class="p">, </span>scaling_down_policies=None<span class="p">, </span>scaling_strategies=None<span class="p">, </span>scaling_target_policies=None<span class="p">, </span>scaling_up_policies=None<span class="p">, </span>scheduled_tasks=None<span class="p">, </span>security_groups=None<span class="p">, </span>shutdown_script=None<span class="p">, </span>signals=None<span class="p">, </span>spot_percentage=None<span class="p">, </span>stateful_deallocation=None<span class="p">, </span>subnet_ids=None<span class="p">, </span>tags=None<span class="p">, </span>target_group_arns=None<span class="p">, </span>update_policy=None<span class="p">, </span>user_data=None<span class="p">, </span>utilize_reserved_instances=None<span class="p">, </span>wait_for_capacity=None<span class="p">, </span>wait_for_capacity_timeout=None<span class="p">, __props__=None);</span></code></pre></div>
{{% /choosable %}}

{{% choosable language go %}}
<div class="highlight"><pre class="chroma"><code class="language-go" data-lang="go"><span class="k">func </span>GetElastigroup<span class="p">(</span><span class="nx">ctx</span> *<span class="nx"><a href="https://pkg.go.dev/github.com/pulumi/pulumi/sdk/go/pulumi?tab=doc#Context">Context</a></span><span class="p">, </span><span class="nx">name</span> <span class="nx"><a href="https://golang.org/pkg/builtin/#string">string</a></span><span class="p">, </span><span class="nx">id</span> <span class="nx"><a href="https://pkg.go.dev/github.com/pulumi/pulumi/sdk/go/pulumi?tab=doc#IDInput">IDInput</a></span><span class="p">, </span><span class="nx">state</span> *<span class="nx"><a href="https://pkg.go.dev/github.com/pulumi/pulumi-spotinst/sdk/go/spotinst/aws?tab=doc#ElastigroupState">ElastigroupState</a></span><span class="p">, </span><span class="nx">opts</span> ...<span class="nx"><a href="https://pkg.go.dev/github.com/pulumi/pulumi/sdk/go/pulumi?tab=doc#ResourceOption">ResourceOption</a></span><span class="p">) (*<span class="nx"><a href="https://pkg.go.dev/github.com/pulumi/pulumi-spotinst/sdk/go/spotinst/aws?tab=doc#Elastigroup">Elastigroup</a></span>, error)</span></code></pre></div>
{{% /choosable %}}

{{% choosable language csharp %}}
<div class="highlight"><pre class="chroma"><code class="language-csharp" data-lang="csharp"><span class="k">public static </span><span class="nx"><a href="/docs/reference/pkg/dotnet/Pulumi.Spotinst/Pulumi.Spotinst.Aws.Elastigroup.html">Elastigroup</a></span><span class="nf"> Get</span><span class="p">(</span><span class="nx"><a href="https://docs.microsoft.com/en-us/dotnet/csharp/language-reference/builtin-types/built-in-types">string</a></span> <span class="nx">name<span class="p">, </span><span class="nx"><a href="/docs/reference/pkg/dotnet/Pulumi/Pulumi.Input.html">Input&lt;string&gt;</a></span> <span class="nx">id<span class="p">, </span><span class="nx"><a href="/docs/reference/pkg/dotnet/Pulumi.Spotinst/Pulumi.Spotinst.Aws.ElastigroupState.html">ElastigroupState</a></span>? <span class="nx">state<span class="p">, </span><span class="nx"><a href="/docs/reference/pkg/dotnet/Pulumi/Pulumi.CustomResourceOptions.html">CustomResourceOptions</a></span>? <span class="nx">opts = null<span class="p">)</span></code></pre></div>
{{% /choosable %}}

{{% choosable language nodejs %}}

<dl class="resources-properties">
    <dt class="property-required" title="Required">
        <span>name</span>
        <span class="property-indicator"></span>
    </dt>
    <dd>The unique name of the resulting resource.</dd>
    <dt class="property-required" title="Required">
        <span>id</span>
        <span class="property-indicator"></span>
    </dt>
    <dd>The <em>unique</em> provider ID of the resource to lookup.</dd>
    <dt class="property-optional" title="Optional">
        <span>state</span>
        <span class="property-indicator"></span>
    </dt>
    <dd>Any extra arguments used during the lookup.</dd>
    <dt class="property-optional" title="Optional">
        <span>opts</span>
        <span class="property-indicator"></span>
    </dt>
    <dd>A bag of options that control this resource's behavior.</dd>
</dl>

{{% /choosable %}}

{{% choosable language python %}}
<dl class="resources-properties">
    <dt class="property-required" title="Required">
        <span>resource_name</span>
        <span class="property-indicator"></span>
    </dt>
    <dd>The unique name of the resulting resource.</dd>
    <dt class="property-required" title="Optional">
        <span>id</span>
        <span class="property-indicator"></span>
    </dt>
    <dd>The <em>unique</em> provider ID of the resource to lookup.</dd>
</dl>
{{% /choosable %}}

{{% choosable language go %}}

<dl class="resources-properties">
    <dt class="property-required" title="Required">
        <span>name</span>
        <span class="property-indicator"></span>
    </dt>
    <dd>The unique name of the resulting resource.</dd>
    <dt class="property-required" title="Required">
        <span>id</span>
        <span class="property-indicator"></span>
    </dt>
    <dd>The <em>unique</em> provider ID of the resource to lookup.</dd>
    <dt class="property-optional" title="Optional">
        <span>state</span>
        <span class="property-indicator"></span>
    </dt>
    <dd>Any extra arguments used during the lookup.</dd>
    <dt class="property-optional" title="Optional">
        <span>opts</span>
        <span class="property-indicator"></span>
    </dt>
    <dd>A bag of options that control this resource's behavior.</dd>
</dl>

{{% /choosable %}}

{{% choosable language csharp %}}

<dl class="resources-properties">
    <dt class="property-required" title="Required">
        <span>name</span>
        <span class="property-indicator"></span>
    </dt>
    <dd>The unique name of the resulting resource.</dd>
    <dt class="property-required" title="Required">
        <span>id</span>
        <span class="property-indicator"></span>
    </dt>
    <dd>The <em>unique</em> provider ID of the resource to lookup.</dd>
    <dt class="property-optional" title="Optional">
        <span>state</span>
        <span class="property-indicator"></span>
    </dt>
    <dd>Any extra arguments used during the lookup.</dd>
    <dt class="property-optional" title="Optional">
        <span>opts</span>
        <span class="property-indicator"></span>
    </dt>
    <dd>A bag of options that control this resource's behavior.</dd>
</dl>

{{% /choosable %}}

The following state arguments are supported:



{{% choosable language csharp %}}
<dl class="resources-properties">

    <dt class="property-optional"
            title="Optional">
        <span>Availability<wbr>Zones</span>
        <span class="property-indicator"></span>
        <span class="property-type">List<string>?</span>
    </dt>
    <dd>{{% md %}}List of Strings of availability zones. When this parameter is set, `subnet_ids` should be left unused.
Note: `availability_zones` naming syntax follows the convention `availability-zone:subnet:placement-group-name`. For example, to set an AZ in `us-east-1` with subnet `subnet-123456` and placement group `ClusterI03`, you would set:
`availability_zones = ["us-east-1a:subnet-123456:ClusterI03"]`
{{% /md %}}</dd>

    <dt class="property-optional"
            title="Optional">
        <span>Block<wbr>Devices<wbr>Mode</span>
        <span class="property-indicator"></span>
        <span class="property-type">string?</span>
    </dt>
    <dd>{{% md %}}{{% /md %}}</dd>

    <dt class="property-optional"
            title="Optional">
        <span>Capacity<wbr>Unit</span>
        <span class="property-indicator"></span>
        <span class="property-type">string?</span>
    </dt>
    <dd>{{% md %}}The capacity unit to launch instances by. If not specified, when choosing the weight unit, each instance will weight as the number of its vCPUs.
{{% /md %}}</dd>

    <dt class="property-optional"
            title="Optional">
        <span>Cpu<wbr>Credits</span>
        <span class="property-indicator"></span>
        <span class="property-type">string?</span>
    </dt>
    <dd>{{% md %}}Controls how T3 instances are launched. Valid values: `standard`, `unlimited`.
{{% /md %}}</dd>

    <dt class="property-optional"
            title="Optional">
        <span>Description</span>
        <span class="property-indicator"></span>
        <span class="property-type">string?</span>
    </dt>
    <dd>{{% md %}}The group description.
{{% /md %}}</dd>

    <dt class="property-optional"
            title="Optional">
        <span>Desired<wbr>Capacity</span>
        <span class="property-indicator"></span>
        <span class="property-type">int?</span>
    </dt>
    <dd>{{% md %}}The desired number of instances the group should have at any time.
{{% /md %}}</dd>

    <dt class="property-optional"
            title="Optional">
        <span>Draining<wbr>Timeout</span>
        <span class="property-indicator"></span>
        <span class="property-type">int?</span>
    </dt>
    <dd>{{% md %}}The time in seconds, the instance is allowed to run while detached from the ELB. This is to allow the instance time to be drained from incoming TCP connections before terminating it, during a scale down operation.
{{% /md %}}</dd>

    <dt class="property-optional"
            title="Optional">
        <span>Ebs<wbr>Block<wbr>Devices</span>
        <span class="property-indicator"></span>
        <span class="property-type"><a href="#elastigroupebsblockdevice">List&lt;Elastigroup<wbr>Ebs<wbr>Block<wbr>Device<wbr>Args&gt;?</a></span>
    </dt>
    <dd>{{% md %}}{{% /md %}}</dd>

    <dt class="property-optional"
            title="Optional">
        <span>Ebs<wbr>Optimized</span>
        <span class="property-indicator"></span>
        <span class="property-type">bool?</span>
    </dt>
    <dd>{{% md %}}Enable high bandwidth connectivity between instances and AWS’s Elastic Block Store (EBS). For instance types that are EBS-optimized by default this parameter will be ignored.
{{% /md %}}</dd>

    <dt class="property-optional"
            title="Optional">
        <span>Elastic<wbr>Ips</span>
        <span class="property-indicator"></span>
        <span class="property-type">List<string>?</span>
    </dt>
    <dd>{{% md %}}A list of [AWS Elastic IP](http://docs.aws.amazon.com/AWSEC2/latest/UserGuide/elastic-ip-addresses-eip.html) allocation IDs to associate to the group instances.
{{% /md %}}</dd>

    <dt class="property-optional"
            title="Optional">
        <span>Elastic<wbr>Load<wbr>Balancers</span>
        <span class="property-indicator"></span>
        <span class="property-type">List<string>?</span>
    </dt>
    <dd>{{% md %}}{{% /md %}}</dd>

    <dt class="property-optional"
            title="Optional">
        <span>Enable<wbr>Monitoring</span>
        <span class="property-indicator"></span>
        <span class="property-type">bool?</span>
    </dt>
    <dd>{{% md %}}Indicates whether monitoring is enabled for the instance.
{{% /md %}}</dd>

    <dt class="property-optional"
            title="Optional">
        <span>Ephemeral<wbr>Block<wbr>Devices</span>
        <span class="property-indicator"></span>
        <span class="property-type"><a href="#elastigroupephemeralblockdevice">List&lt;Elastigroup<wbr>Ephemeral<wbr>Block<wbr>Device<wbr>Args&gt;?</a></span>
    </dt>
    <dd>{{% md %}}{{% /md %}}</dd>

    <dt class="property-optional"
            title="Optional">
        <span>Fallback<wbr>To<wbr>Ondemand</span>
        <span class="property-indicator"></span>
        <span class="property-type">bool?</span>
    </dt>
    <dd>{{% md %}}In a case of no Spot instances available, Elastigroup will launch on-demand instances instead.
{{% /md %}}</dd>

    <dt class="property-optional"
            title="Optional">
        <span>Health<wbr>Check<wbr>Grace<wbr>Period</span>
        <span class="property-indicator"></span>
        <span class="property-type">int?</span>
    </dt>
    <dd>{{% md %}}The amount of time, in seconds, after the instance has launched to starts and check its health.
{{% /md %}}</dd>

    <dt class="property-optional"
            title="Optional">
        <span>Health<wbr>Check<wbr>Type</span>
        <span class="property-indicator"></span>
        <span class="property-type">string?</span>
    </dt>
    <dd>{{% md %}}The service that will perform health checks for the instance. Valid values: `"ELB"`, `"HCS"`, `"TARGET_GROUP"`, `"MLB"`, `"EC2"`, `"MULTAI_TARGET_SET"`, `"MLB_RUNTIME"`, `"K8S_NODE"`, `"NOMAD_NODE"`, `"ECS_CLUSTER_INSTANCE"`.
{{% /md %}}</dd>

    <dt class="property-optional"
            title="Optional">
        <span>Health<wbr>Check<wbr>Unhealthy<wbr>Duration<wbr>Before<wbr>Replacement</span>
        <span class="property-indicator"></span>
        <span class="property-type">int?</span>
    </dt>
    <dd>{{% md %}}The amount of time, in seconds, that we will wait before replacing an instance that is running and became unhealthy (this is only applicable for instances that were once healthy).
{{% /md %}}</dd>

    <dt class="property-optional"
            title="Optional">
        <span>Iam<wbr>Instance<wbr>Profile</span>
        <span class="property-indicator"></span>
        <span class="property-type">string?</span>
    </dt>
    <dd>{{% md %}}The ARN or name of an IAM instance profile to associate with launched instances.
{{% /md %}}</dd>

    <dt class="property-optional"
            title="Optional">
        <span>Image<wbr>Id</span>
        <span class="property-indicator"></span>
        <span class="property-type">string?</span>
    </dt>
    <dd>{{% md %}}The ID of the AMI used to launch the instance.
{{% /md %}}</dd>

    <dt class="property-optional"
            title="Optional">
        <span>Instance<wbr>Types<wbr>Ondemand</span>
        <span class="property-indicator"></span>
        <span class="property-type">string?</span>
    </dt>
    <dd>{{% md %}}The type of instance determines your instance's CPU capacity, memory and storage (e.g., m1.small, c1.xlarge).
{{% /md %}}</dd>

    <dt class="property-optional"
            title="Optional">
        <span>Instance<wbr>Types<wbr>Preferred<wbr>Spots</span>
        <span class="property-indicator"></span>
        <span class="property-type">List<string>?</span>
    </dt>
    <dd>{{% md %}}Prioritize a subset of spot instance types. Must be a subset of the selected spot instance types.
{{% /md %}}</dd>

    <dt class="property-optional"
            title="Optional">
        <span>Instance<wbr>Types<wbr>Spots</span>
        <span class="property-indicator"></span>
        <span class="property-type">List<string>?</span>
    </dt>
    <dd>{{% md %}}One or more instance types.
{{% /md %}}</dd>

    <dt class="property-optional"
            title="Optional">
        <span>Instance<wbr>Types<wbr>Weights</span>
        <span class="property-indicator"></span>
        <span class="property-type"><a href="#elastigroupinstancetypesweight">List&lt;Elastigroup<wbr>Instance<wbr>Types<wbr>Weight<wbr>Args&gt;?</a></span>
    </dt>
    <dd>{{% md %}}List of weights per instance type for weighted groups. Each object in the list should have the following attributes:
{{% /md %}}</dd>

    <dt class="property-optional"
            title="Optional">
        <span>Integration<wbr>Beanstalk</span>
        <span class="property-indicator"></span>
        <span class="property-type"><a href="#elastigroupintegrationbeanstalk">Elastigroup<wbr>Integration<wbr>Beanstalk<wbr>Args?</a></span>
    </dt>
    <dd>{{% md %}}{{% /md %}}</dd>

    <dt class="property-optional"
            title="Optional">
        <span>Integration<wbr>Codedeploy</span>
        <span class="property-indicator"></span>
        <span class="property-type"><a href="#elastigroupintegrationcodedeploy">Elastigroup<wbr>Integration<wbr>Codedeploy<wbr>Args?</a></span>
    </dt>
    <dd>{{% md %}}{{% /md %}}</dd>

    <dt class="property-optional"
            title="Optional">
        <span>Integration<wbr>Docker<wbr>Swarm</span>
        <span class="property-indicator"></span>
        <span class="property-type"><a href="#elastigroupintegrationdockerswarm">Elastigroup<wbr>Integration<wbr>Docker<wbr>Swarm<wbr>Args?</a></span>
    </dt>
    <dd>{{% md %}}{{% /md %}}</dd>

    <dt class="property-optional"
            title="Optional">
        <span>Integration<wbr>Ecs</span>
        <span class="property-indicator"></span>
        <span class="property-type"><a href="#elastigroupintegrationecs">Elastigroup<wbr>Integration<wbr>Ecs<wbr>Args?</a></span>
    </dt>
    <dd>{{% md %}}{{% /md %}}</dd>

    <dt class="property-optional"
            title="Optional">
        <span>Integration<wbr>Gitlab</span>
        <span class="property-indicator"></span>
        <span class="property-type"><a href="#elastigroupintegrationgitlab">Elastigroup<wbr>Integration<wbr>Gitlab<wbr>Args?</a></span>
    </dt>
    <dd>{{% md %}}{{% /md %}}</dd>

    <dt class="property-optional"
            title="Optional">
        <span>Integration<wbr>Kubernetes</span>
        <span class="property-indicator"></span>
        <span class="property-type"><a href="#elastigroupintegrationkubernetes">Elastigroup<wbr>Integration<wbr>Kubernetes<wbr>Args?</a></span>
    </dt>
    <dd>{{% md %}}{{% /md %}}</dd>

    <dt class="property-optional"
            title="Optional">
        <span>Integration<wbr>Mesosphere</span>
        <span class="property-indicator"></span>
        <span class="property-type"><a href="#elastigroupintegrationmesosphere">Elastigroup<wbr>Integration<wbr>Mesosphere<wbr>Args?</a></span>
    </dt>
    <dd>{{% md %}}{{% /md %}}</dd>

    <dt class="property-optional"
            title="Optional">
        <span>Integration<wbr>Multai<wbr>Runtime</span>
        <span class="property-indicator"></span>
        <span class="property-type"><a href="#elastigroupintegrationmultairuntime">Elastigroup<wbr>Integration<wbr>Multai<wbr>Runtime<wbr>Args?</a></span>
    </dt>
    <dd>{{% md %}}{{% /md %}}</dd>

    <dt class="property-optional"
            title="Optional">
        <span>Integration<wbr>Nomad</span>
        <span class="property-indicator"></span>
        <span class="property-type"><a href="#elastigroupintegrationnomad">Elastigroup<wbr>Integration<wbr>Nomad<wbr>Args?</a></span>
    </dt>
    <dd>{{% md %}}{{% /md %}}</dd>

    <dt class="property-optional"
            title="Optional">
        <span>Integration<wbr>Rancher</span>
        <span class="property-indicator"></span>
        <span class="property-type"><a href="#elastigroupintegrationrancher">Elastigroup<wbr>Integration<wbr>Rancher<wbr>Args?</a></span>
    </dt>
    <dd>{{% md %}}{{% /md %}}</dd>

    <dt class="property-optional"
            title="Optional">
        <span>Integration<wbr>Route53</span>
        <span class="property-indicator"></span>
        <span class="property-type"><a href="#elastigroupintegrationroute53">Elastigroup<wbr>Integration<wbr>Route53Args?</a></span>
    </dt>
    <dd>{{% md %}}{{% /md %}}</dd>

    <dt class="property-optional"
            title="Optional">
        <span>Key<wbr>Name</span>
        <span class="property-indicator"></span>
        <span class="property-type">string?</span>
    </dt>
    <dd>{{% md %}}The key name that should be used for the instance.
{{% /md %}}</dd>

    <dt class="property-optional"
            title="Optional">
        <span>Lifetime<wbr>Period</span>
        <span class="property-indicator"></span>
        <span class="property-type">string?</span>
    </dt>
    <dd>{{% md %}}{{% /md %}}</dd>

    <dt class="property-optional"
            title="Optional">
        <span>Max<wbr>Size</span>
        <span class="property-indicator"></span>
        <span class="property-type">int?</span>
    </dt>
    <dd>{{% md %}}The maximum number of instances the group should have at any time.
{{% /md %}}</dd>

    <dt class="property-optional"
            title="Optional">
        <span>Min<wbr>Size</span>
        <span class="property-indicator"></span>
        <span class="property-type">int?</span>
    </dt>
    <dd>{{% md %}}The minimum number of instances the group should have at any time.
{{% /md %}}</dd>

    <dt class="property-optional"
            title="Optional">
        <span>Multai<wbr>Target<wbr>Sets</span>
        <span class="property-indicator"></span>
        <span class="property-type"><a href="#elastigroupmultaitargetset">List&lt;Elastigroup<wbr>Multai<wbr>Target<wbr>Set<wbr>Args&gt;?</a></span>
    </dt>
    <dd>{{% md %}}{{% /md %}}</dd>

    <dt class="property-optional"
            title="Optional">
        <span>Name</span>
        <span class="property-indicator"></span>
        <span class="property-type">string?</span>
    </dt>
    <dd>{{% md %}}The group name.
{{% /md %}}</dd>

    <dt class="property-optional"
            title="Optional">
        <span>Network<wbr>Interfaces</span>
        <span class="property-indicator"></span>
        <span class="property-type"><a href="#elastigroupnetworkinterface">List&lt;Elastigroup<wbr>Network<wbr>Interface<wbr>Args&gt;?</a></span>
    </dt>
    <dd>{{% md %}}{{% /md %}}</dd>

    <dt class="property-optional"
            title="Optional">
        <span>Ondemand<wbr>Count</span>
        <span class="property-indicator"></span>
        <span class="property-type">int?</span>
    </dt>
    <dd>{{% md %}}Number of on demand instances to launch in the group. All other instances will be spot instances. When this parameter is set the `spot_percentage` parameter is being ignored.
{{% /md %}}</dd>

    <dt class="property-optional"
            title="Optional">
        <span>Orientation</span>
        <span class="property-indicator"></span>
        <span class="property-type">string?</span>
    </dt>
    <dd>{{% md %}}Select a prediction strategy. Valid values: `"balanced"`, `"costOriented"`, `"equalAzDistribution"`, `"availabilityOriented"`.    
{{% /md %}}</dd>

    <dt class="property-optional"
            title="Optional">
        <span>Persist<wbr>Block<wbr>Devices</span>
        <span class="property-indicator"></span>
        <span class="property-type">bool?</span>
    </dt>
    <dd>{{% md %}}{{% /md %}}</dd>

    <dt class="property-optional"
            title="Optional">
        <span>Persist<wbr>Private<wbr>Ip</span>
        <span class="property-indicator"></span>
        <span class="property-type">bool?</span>
    </dt>
    <dd>{{% md %}}{{% /md %}}</dd>

    <dt class="property-optional"
            title="Optional">
        <span>Persist<wbr>Root<wbr>Device</span>
        <span class="property-indicator"></span>
        <span class="property-type">bool?</span>
    </dt>
    <dd>{{% md %}}{{% /md %}}</dd>

    <dt class="property-optional"
            title="Optional">
        <span>Placement<wbr>Tenancy</span>
        <span class="property-indicator"></span>
        <span class="property-type">string?</span>
    </dt>
    <dd>{{% md %}}Enable dedicated tenancy. Note: There is a flat hourly fee for each region in which dedicated tenancy is used.
{{% /md %}}</dd>

    <dt class="property-optional"
            title="Optional">
        <span>Preferred<wbr>Availability<wbr>Zones</span>
        <span class="property-indicator"></span>
        <span class="property-type">List<string>?</span>
    </dt>
    <dd>{{% md %}}The AZs to prioritize when launching Spot instances. If no markets are available in the Preferred AZs, Spot instances are launched in the non-preferred AZs. 
Note: Must be a sublist of `availability_zones` and `orientation` value must not be `"equalAzDistribution"`.
{{% /md %}}</dd>

    <dt class="property-optional"
            title="Optional">
        <span>Private<wbr>Ips</span>
        <span class="property-indicator"></span>
        <span class="property-type">List<string>?</span>
    </dt>
    <dd>{{% md %}}{{% /md %}}</dd>

    <dt class="property-optional"
            title="Optional">
        <span>Product</span>
        <span class="property-indicator"></span>
        <span class="property-type">string?</span>
    </dt>
    <dd>{{% md %}}Operation system type. Valid values: `"Linux/UNIX"`, `"SUSE Linux"`, `"Windows"`. 
For EC2 Classic instances:  `"Linux/UNIX (Amazon VPC)"`, `"SUSE Linux (Amazon VPC)"`, `"Windows (Amazon VPC)"`.
{{% /md %}}</dd>

    <dt class="property-optional"
            title="Optional">
        <span>Region</span>
        <span class="property-indicator"></span>
        <span class="property-type">string?</span>
    </dt>
    <dd>{{% md %}}The AWS region your group will be created in.
Note: This parameter is required if you specify subnets (through subnet_ids). This parameter is optional if you specify Availability Zones (through availability_zones).
{{% /md %}}</dd>

    <dt class="property-optional"
            title="Optional">
        <span>Revert<wbr>To<wbr>Spot</span>
        <span class="property-indicator"></span>
        <span class="property-type"><a href="#elastigroupreverttospot">Elastigroup<wbr>Revert<wbr>To<wbr>Spot<wbr>Args?</a></span>
    </dt>
    <dd>{{% md %}}Hold settings for strategy correction – replacing On-Demand for Spot instances. Supported Values: `"never"`, `"always"`, `"timeWindow"`
{{% /md %}}</dd>

    <dt class="property-optional"
            title="Optional">
        <span>Scaling<wbr>Down<wbr>Policies</span>
        <span class="property-indicator"></span>
        <span class="property-type"><a href="#elastigroupscalingdownpolicy">List&lt;Elastigroup<wbr>Scaling<wbr>Down<wbr>Policy<wbr>Args&gt;?</a></span>
    </dt>
    <dd>{{% md %}}{{% /md %}}</dd>

    <dt class="property-optional"
            title="Optional">
        <span>Scaling<wbr>Strategies</span>
        <span class="property-indicator"></span>
        <span class="property-type"><a href="#elastigroupscalingstrategy">List&lt;Elastigroup<wbr>Scaling<wbr>Strategy<wbr>Args&gt;?</a></span>
    </dt>
    <dd>{{% md %}}Set termination policy.
{{% /md %}}</dd>

    <dt class="property-optional"
            title="Optional">
        <span>Scaling<wbr>Target<wbr>Policies</span>
        <span class="property-indicator"></span>
        <span class="property-type"><a href="#elastigroupscalingtargetpolicy">List&lt;Elastigroup<wbr>Scaling<wbr>Target<wbr>Policy<wbr>Args&gt;?</a></span>
    </dt>
    <dd>{{% md %}}{{% /md %}}</dd>

    <dt class="property-optional"
            title="Optional">
        <span>Scaling<wbr>Up<wbr>Policies</span>
        <span class="property-indicator"></span>
        <span class="property-type"><a href="#elastigroupscalinguppolicy">List&lt;Elastigroup<wbr>Scaling<wbr>Up<wbr>Policy<wbr>Args&gt;?</a></span>
    </dt>
    <dd>{{% md %}}{{% /md %}}</dd>

    <dt class="property-optional"
            title="Optional">
        <span>Scheduled<wbr>Tasks</span>
        <span class="property-indicator"></span>
        <span class="property-type"><a href="#elastigroupscheduledtask">List&lt;Elastigroup<wbr>Scheduled<wbr>Task<wbr>Args&gt;?</a></span>
    </dt>
    <dd>{{% md %}}{{% /md %}}</dd>

    <dt class="property-optional"
            title="Optional">
        <span>Security<wbr>Groups</span>
        <span class="property-indicator"></span>
        <span class="property-type">List<string>?</span>
    </dt>
    <dd>{{% md %}}A list of associated security group IDS.
{{% /md %}}</dd>

    <dt class="property-optional"
            title="Optional">
        <span>Shutdown<wbr>Script</span>
        <span class="property-indicator"></span>
        <span class="property-type">string?</span>
    </dt>
    <dd>{{% md %}}The Base64-encoded shutdown script that executes prior to instance termination, for more information please see: [Shutdown Script](https://api.spotinst.com/integration-docs/elastigroup/concepts/compute-concepts/shutdown-scripts/)
{{% /md %}}</dd>

    <dt class="property-optional"
            title="Optional">
        <span>Signals</span>
        <span class="property-indicator"></span>
        <span class="property-type"><a href="#elastigroupsignal">List&lt;Elastigroup<wbr>Signal<wbr>Args&gt;?</a></span>
    </dt>
    <dd>{{% md %}}{{% /md %}}</dd>

    <dt class="property-optional"
            title="Optional">
        <span>Spot<wbr>Percentage</span>
        <span class="property-indicator"></span>
        <span class="property-type">double?</span>
    </dt>
    <dd>{{% md %}}The percentage of Spot instances that would spin up from the `desired_capacity` number.
{{% /md %}}</dd>

    <dt class="property-optional"
            title="Optional">
        <span>Stateful<wbr>Deallocation</span>
        <span class="property-indicator"></span>
        <span class="property-type"><a href="#elastigroupstatefuldeallocation">Elastigroup<wbr>Stateful<wbr>Deallocation<wbr>Args?</a></span>
    </dt>
    <dd>{{% md %}}{{% /md %}}</dd>

    <dt class="property-optional"
            title="Optional">
        <span>Subnet<wbr>Ids</span>
        <span class="property-indicator"></span>
        <span class="property-type">List<string>?</span>
    </dt>
    <dd>{{% md %}}List of Strings of subnet identifiers.
Note: When this parameter is set, `availability_zones` should be left unused.
{{% /md %}}</dd>

    <dt class="property-optional"
            title="Optional">
        <span>Tags</span>
        <span class="property-indicator"></span>
        <span class="property-type"><a href="#elastigrouptag">List&lt;Elastigroup<wbr>Tag<wbr>Args&gt;?</a></span>
    </dt>
    <dd>{{% md %}}A key/value mapping of tags to assign to the resource.
{{% /md %}}</dd>

    <dt class="property-optional"
            title="Optional">
        <span>Target<wbr>Group<wbr>Arns</span>
        <span class="property-indicator"></span>
        <span class="property-type">List<string>?</span>
    </dt>
    <dd>{{% md %}}{{% /md %}}</dd>

    <dt class="property-optional"
            title="Optional">
        <span>Update<wbr>Policy</span>
        <span class="property-indicator"></span>
        <span class="property-type"><a href="#elastigroupupdatepolicy">Elastigroup<wbr>Update<wbr>Policy<wbr>Args?</a></span>
    </dt>
    <dd>{{% md %}}{{% /md %}}</dd>

    <dt class="property-optional"
            title="Optional">
        <span>User<wbr>Data</span>
        <span class="property-indicator"></span>
        <span class="property-type">string?</span>
    </dt>
    <dd>{{% md %}}The user data to provide when launching the instance.
{{% /md %}}</dd>

    <dt class="property-optional"
            title="Optional">
        <span>Utilize<wbr>Reserved<wbr>Instances</span>
        <span class="property-indicator"></span>
        <span class="property-type">bool?</span>
    </dt>
    <dd>{{% md %}}In a case of any available reserved instances, Elastigroup will utilize them first before purchasing Spot instances.
{{% /md %}}</dd>

    <dt class="property-optional"
            title="Optional">
        <span>Wait<wbr>For<wbr>Capacity</span>
        <span class="property-indicator"></span>
        <span class="property-type">int?</span>
    </dt>
    <dd>{{% md %}}Minimum number of instances in a 'HEALTHY' status that is required before continuing. This is ignored when updating with blue/green deployment. Cannot exceed `desired_capacity`.
{{% /md %}}</dd>

    <dt class="property-optional"
            title="Optional">
        <span>Wait<wbr>For<wbr>Capacity<wbr>Timeout</span>
        <span class="property-indicator"></span>
        <span class="property-type">int?</span>
    </dt>
    <dd>{{% md %}}Time (seconds) to wait for instances to report a 'HEALTHY' status. Useful for plans with multiple dependencies that take some time to initialize. Leave undefined or set to `0` to indicate no wait. This is ignored when updating with blue/green deployment. 
{{% /md %}}</dd>

</dl>
{{% /choosable %}}


{{% choosable language go %}}
<dl class="resources-properties">

    <dt class="property-optional"
            title="Optional">
        <span>Availability<wbr>Zones</span>
        <span class="property-indicator"></span>
        <span class="property-type">[]string</span>
    </dt>
    <dd>{{% md %}}List of Strings of availability zones. When this parameter is set, `subnet_ids` should be left unused.
Note: `availability_zones` naming syntax follows the convention `availability-zone:subnet:placement-group-name`. For example, to set an AZ in `us-east-1` with subnet `subnet-123456` and placement group `ClusterI03`, you would set:
`availability_zones = ["us-east-1a:subnet-123456:ClusterI03"]`
{{% /md %}}</dd>

    <dt class="property-optional"
            title="Optional">
        <span>Block<wbr>Devices<wbr>Mode</span>
        <span class="property-indicator"></span>
        <span class="property-type">*string</span>
    </dt>
    <dd>{{% md %}}{{% /md %}}</dd>

    <dt class="property-optional"
            title="Optional">
        <span>Capacity<wbr>Unit</span>
        <span class="property-indicator"></span>
        <span class="property-type">*string</span>
    </dt>
    <dd>{{% md %}}The capacity unit to launch instances by. If not specified, when choosing the weight unit, each instance will weight as the number of its vCPUs.
{{% /md %}}</dd>

    <dt class="property-optional"
            title="Optional">
        <span>Cpu<wbr>Credits</span>
        <span class="property-indicator"></span>
        <span class="property-type">*string</span>
    </dt>
    <dd>{{% md %}}Controls how T3 instances are launched. Valid values: `standard`, `unlimited`.
{{% /md %}}</dd>

    <dt class="property-optional"
            title="Optional">
        <span>Description</span>
        <span class="property-indicator"></span>
        <span class="property-type">*string</span>
    </dt>
    <dd>{{% md %}}The group description.
{{% /md %}}</dd>

    <dt class="property-optional"
            title="Optional">
        <span>Desired<wbr>Capacity</span>
        <span class="property-indicator"></span>
        <span class="property-type">*int</span>
    </dt>
    <dd>{{% md %}}The desired number of instances the group should have at any time.
{{% /md %}}</dd>

    <dt class="property-optional"
            title="Optional">
        <span>Draining<wbr>Timeout</span>
        <span class="property-indicator"></span>
        <span class="property-type">*int</span>
    </dt>
    <dd>{{% md %}}The time in seconds, the instance is allowed to run while detached from the ELB. This is to allow the instance time to be drained from incoming TCP connections before terminating it, during a scale down operation.
{{% /md %}}</dd>

    <dt class="property-optional"
            title="Optional">
        <span>Ebs<wbr>Block<wbr>Devices</span>
        <span class="property-indicator"></span>
        <span class="property-type"><a href="#elastigroupebsblockdevice">[]Elastigroup<wbr>Ebs<wbr>Block<wbr>Device</a></span>
    </dt>
    <dd>{{% md %}}{{% /md %}}</dd>

    <dt class="property-optional"
            title="Optional">
        <span>Ebs<wbr>Optimized</span>
        <span class="property-indicator"></span>
        <span class="property-type">*bool</span>
    </dt>
    <dd>{{% md %}}Enable high bandwidth connectivity between instances and AWS’s Elastic Block Store (EBS). For instance types that are EBS-optimized by default this parameter will be ignored.
{{% /md %}}</dd>

    <dt class="property-optional"
            title="Optional">
        <span>Elastic<wbr>Ips</span>
        <span class="property-indicator"></span>
        <span class="property-type">[]string</span>
    </dt>
    <dd>{{% md %}}A list of [AWS Elastic IP](http://docs.aws.amazon.com/AWSEC2/latest/UserGuide/elastic-ip-addresses-eip.html) allocation IDs to associate to the group instances.
{{% /md %}}</dd>

    <dt class="property-optional"
            title="Optional">
        <span>Elastic<wbr>Load<wbr>Balancers</span>
        <span class="property-indicator"></span>
        <span class="property-type">[]string</span>
    </dt>
    <dd>{{% md %}}{{% /md %}}</dd>

    <dt class="property-optional"
            title="Optional">
        <span>Enable<wbr>Monitoring</span>
        <span class="property-indicator"></span>
        <span class="property-type">*bool</span>
    </dt>
    <dd>{{% md %}}Indicates whether monitoring is enabled for the instance.
{{% /md %}}</dd>

    <dt class="property-optional"
            title="Optional">
        <span>Ephemeral<wbr>Block<wbr>Devices</span>
        <span class="property-indicator"></span>
        <span class="property-type"><a href="#elastigroupephemeralblockdevice">[]Elastigroup<wbr>Ephemeral<wbr>Block<wbr>Device</a></span>
    </dt>
    <dd>{{% md %}}{{% /md %}}</dd>

    <dt class="property-optional"
            title="Optional">
        <span>Fallback<wbr>To<wbr>Ondemand</span>
        <span class="property-indicator"></span>
        <span class="property-type">*bool</span>
    </dt>
    <dd>{{% md %}}In a case of no Spot instances available, Elastigroup will launch on-demand instances instead.
{{% /md %}}</dd>

    <dt class="property-optional"
            title="Optional">
        <span>Health<wbr>Check<wbr>Grace<wbr>Period</span>
        <span class="property-indicator"></span>
        <span class="property-type">*int</span>
    </dt>
    <dd>{{% md %}}The amount of time, in seconds, after the instance has launched to starts and check its health.
{{% /md %}}</dd>

    <dt class="property-optional"
            title="Optional">
        <span>Health<wbr>Check<wbr>Type</span>
        <span class="property-indicator"></span>
        <span class="property-type">*string</span>
    </dt>
    <dd>{{% md %}}The service that will perform health checks for the instance. Valid values: `"ELB"`, `"HCS"`, `"TARGET_GROUP"`, `"MLB"`, `"EC2"`, `"MULTAI_TARGET_SET"`, `"MLB_RUNTIME"`, `"K8S_NODE"`, `"NOMAD_NODE"`, `"ECS_CLUSTER_INSTANCE"`.
{{% /md %}}</dd>

    <dt class="property-optional"
            title="Optional">
        <span>Health<wbr>Check<wbr>Unhealthy<wbr>Duration<wbr>Before<wbr>Replacement</span>
        <span class="property-indicator"></span>
        <span class="property-type">*int</span>
    </dt>
    <dd>{{% md %}}The amount of time, in seconds, that we will wait before replacing an instance that is running and became unhealthy (this is only applicable for instances that were once healthy).
{{% /md %}}</dd>

    <dt class="property-optional"
            title="Optional">
        <span>Iam<wbr>Instance<wbr>Profile</span>
        <span class="property-indicator"></span>
        <span class="property-type">*string</span>
    </dt>
    <dd>{{% md %}}The ARN or name of an IAM instance profile to associate with launched instances.
{{% /md %}}</dd>

    <dt class="property-optional"
            title="Optional">
        <span>Image<wbr>Id</span>
        <span class="property-indicator"></span>
        <span class="property-type">*string</span>
    </dt>
    <dd>{{% md %}}The ID of the AMI used to launch the instance.
{{% /md %}}</dd>

    <dt class="property-optional"
            title="Optional">
        <span>Instance<wbr>Types<wbr>Ondemand</span>
        <span class="property-indicator"></span>
        <span class="property-type">*string</span>
    </dt>
    <dd>{{% md %}}The type of instance determines your instance's CPU capacity, memory and storage (e.g., m1.small, c1.xlarge).
{{% /md %}}</dd>

    <dt class="property-optional"
            title="Optional">
        <span>Instance<wbr>Types<wbr>Preferred<wbr>Spots</span>
        <span class="property-indicator"></span>
        <span class="property-type">[]string</span>
    </dt>
    <dd>{{% md %}}Prioritize a subset of spot instance types. Must be a subset of the selected spot instance types.
{{% /md %}}</dd>

    <dt class="property-optional"
            title="Optional">
        <span>Instance<wbr>Types<wbr>Spots</span>
        <span class="property-indicator"></span>
        <span class="property-type">[]string</span>
    </dt>
    <dd>{{% md %}}One or more instance types.
{{% /md %}}</dd>

    <dt class="property-optional"
            title="Optional">
        <span>Instance<wbr>Types<wbr>Weights</span>
        <span class="property-indicator"></span>
        <span class="property-type"><a href="#elastigroupinstancetypesweight">[]Elastigroup<wbr>Instance<wbr>Types<wbr>Weight</a></span>
    </dt>
    <dd>{{% md %}}List of weights per instance type for weighted groups. Each object in the list should have the following attributes:
{{% /md %}}</dd>

    <dt class="property-optional"
            title="Optional">
        <span>Integration<wbr>Beanstalk</span>
        <span class="property-indicator"></span>
        <span class="property-type"><a href="#elastigroupintegrationbeanstalk">*Elastigroup<wbr>Integration<wbr>Beanstalk</a></span>
    </dt>
    <dd>{{% md %}}{{% /md %}}</dd>

    <dt class="property-optional"
            title="Optional">
        <span>Integration<wbr>Codedeploy</span>
        <span class="property-indicator"></span>
        <span class="property-type"><a href="#elastigroupintegrationcodedeploy">*Elastigroup<wbr>Integration<wbr>Codedeploy</a></span>
    </dt>
    <dd>{{% md %}}{{% /md %}}</dd>

    <dt class="property-optional"
            title="Optional">
        <span>Integration<wbr>Docker<wbr>Swarm</span>
        <span class="property-indicator"></span>
        <span class="property-type"><a href="#elastigroupintegrationdockerswarm">*Elastigroup<wbr>Integration<wbr>Docker<wbr>Swarm</a></span>
    </dt>
    <dd>{{% md %}}{{% /md %}}</dd>

    <dt class="property-optional"
            title="Optional">
        <span>Integration<wbr>Ecs</span>
        <span class="property-indicator"></span>
        <span class="property-type"><a href="#elastigroupintegrationecs">*Elastigroup<wbr>Integration<wbr>Ecs</a></span>
    </dt>
    <dd>{{% md %}}{{% /md %}}</dd>

    <dt class="property-optional"
            title="Optional">
        <span>Integration<wbr>Gitlab</span>
        <span class="property-indicator"></span>
        <span class="property-type"><a href="#elastigroupintegrationgitlab">*Elastigroup<wbr>Integration<wbr>Gitlab</a></span>
    </dt>
    <dd>{{% md %}}{{% /md %}}</dd>

    <dt class="property-optional"
            title="Optional">
        <span>Integration<wbr>Kubernetes</span>
        <span class="property-indicator"></span>
        <span class="property-type"><a href="#elastigroupintegrationkubernetes">*Elastigroup<wbr>Integration<wbr>Kubernetes</a></span>
    </dt>
    <dd>{{% md %}}{{% /md %}}</dd>

    <dt class="property-optional"
            title="Optional">
        <span>Integration<wbr>Mesosphere</span>
        <span class="property-indicator"></span>
        <span class="property-type"><a href="#elastigroupintegrationmesosphere">*Elastigroup<wbr>Integration<wbr>Mesosphere</a></span>
    </dt>
    <dd>{{% md %}}{{% /md %}}</dd>

    <dt class="property-optional"
            title="Optional">
        <span>Integration<wbr>Multai<wbr>Runtime</span>
        <span class="property-indicator"></span>
        <span class="property-type"><a href="#elastigroupintegrationmultairuntime">*Elastigroup<wbr>Integration<wbr>Multai<wbr>Runtime</a></span>
    </dt>
    <dd>{{% md %}}{{% /md %}}</dd>

    <dt class="property-optional"
            title="Optional">
        <span>Integration<wbr>Nomad</span>
        <span class="property-indicator"></span>
        <span class="property-type"><a href="#elastigroupintegrationnomad">*Elastigroup<wbr>Integration<wbr>Nomad</a></span>
    </dt>
    <dd>{{% md %}}{{% /md %}}</dd>

    <dt class="property-optional"
            title="Optional">
        <span>Integration<wbr>Rancher</span>
        <span class="property-indicator"></span>
        <span class="property-type"><a href="#elastigroupintegrationrancher">*Elastigroup<wbr>Integration<wbr>Rancher</a></span>
    </dt>
    <dd>{{% md %}}{{% /md %}}</dd>

    <dt class="property-optional"
            title="Optional">
        <span>Integration<wbr>Route53</span>
        <span class="property-indicator"></span>
        <span class="property-type"><a href="#elastigroupintegrationroute53">*Elastigroup<wbr>Integration<wbr>Route53</a></span>
    </dt>
    <dd>{{% md %}}{{% /md %}}</dd>

    <dt class="property-optional"
            title="Optional">
        <span>Key<wbr>Name</span>
        <span class="property-indicator"></span>
        <span class="property-type">*string</span>
    </dt>
    <dd>{{% md %}}The key name that should be used for the instance.
{{% /md %}}</dd>

    <dt class="property-optional"
            title="Optional">
        <span>Lifetime<wbr>Period</span>
        <span class="property-indicator"></span>
        <span class="property-type">*string</span>
    </dt>
    <dd>{{% md %}}{{% /md %}}</dd>

    <dt class="property-optional"
            title="Optional">
        <span>Max<wbr>Size</span>
        <span class="property-indicator"></span>
        <span class="property-type">*int</span>
    </dt>
    <dd>{{% md %}}The maximum number of instances the group should have at any time.
{{% /md %}}</dd>

    <dt class="property-optional"
            title="Optional">
        <span>Min<wbr>Size</span>
        <span class="property-indicator"></span>
        <span class="property-type">*int</span>
    </dt>
    <dd>{{% md %}}The minimum number of instances the group should have at any time.
{{% /md %}}</dd>

    <dt class="property-optional"
            title="Optional">
        <span>Multai<wbr>Target<wbr>Sets</span>
        <span class="property-indicator"></span>
        <span class="property-type"><a href="#elastigroupmultaitargetset">[]Elastigroup<wbr>Multai<wbr>Target<wbr>Set</a></span>
    </dt>
    <dd>{{% md %}}{{% /md %}}</dd>

    <dt class="property-optional"
            title="Optional">
        <span>Name</span>
        <span class="property-indicator"></span>
        <span class="property-type">*string</span>
    </dt>
    <dd>{{% md %}}The group name.
{{% /md %}}</dd>

    <dt class="property-optional"
            title="Optional">
        <span>Network<wbr>Interfaces</span>
        <span class="property-indicator"></span>
        <span class="property-type"><a href="#elastigroupnetworkinterface">[]Elastigroup<wbr>Network<wbr>Interface</a></span>
    </dt>
    <dd>{{% md %}}{{% /md %}}</dd>

    <dt class="property-optional"
            title="Optional">
        <span>Ondemand<wbr>Count</span>
        <span class="property-indicator"></span>
        <span class="property-type">*int</span>
    </dt>
    <dd>{{% md %}}Number of on demand instances to launch in the group. All other instances will be spot instances. When this parameter is set the `spot_percentage` parameter is being ignored.
{{% /md %}}</dd>

    <dt class="property-optional"
            title="Optional">
        <span>Orientation</span>
        <span class="property-indicator"></span>
        <span class="property-type">*string</span>
    </dt>
    <dd>{{% md %}}Select a prediction strategy. Valid values: `"balanced"`, `"costOriented"`, `"equalAzDistribution"`, `"availabilityOriented"`.    
{{% /md %}}</dd>

    <dt class="property-optional"
            title="Optional">
        <span>Persist<wbr>Block<wbr>Devices</span>
        <span class="property-indicator"></span>
        <span class="property-type">*bool</span>
    </dt>
    <dd>{{% md %}}{{% /md %}}</dd>

    <dt class="property-optional"
            title="Optional">
        <span>Persist<wbr>Private<wbr>Ip</span>
        <span class="property-indicator"></span>
        <span class="property-type">*bool</span>
    </dt>
    <dd>{{% md %}}{{% /md %}}</dd>

    <dt class="property-optional"
            title="Optional">
        <span>Persist<wbr>Root<wbr>Device</span>
        <span class="property-indicator"></span>
        <span class="property-type">*bool</span>
    </dt>
    <dd>{{% md %}}{{% /md %}}</dd>

    <dt class="property-optional"
            title="Optional">
        <span>Placement<wbr>Tenancy</span>
        <span class="property-indicator"></span>
        <span class="property-type">*string</span>
    </dt>
    <dd>{{% md %}}Enable dedicated tenancy. Note: There is a flat hourly fee for each region in which dedicated tenancy is used.
{{% /md %}}</dd>

    <dt class="property-optional"
            title="Optional">
        <span>Preferred<wbr>Availability<wbr>Zones</span>
        <span class="property-indicator"></span>
        <span class="property-type">[]string</span>
    </dt>
    <dd>{{% md %}}The AZs to prioritize when launching Spot instances. If no markets are available in the Preferred AZs, Spot instances are launched in the non-preferred AZs. 
Note: Must be a sublist of `availability_zones` and `orientation` value must not be `"equalAzDistribution"`.
{{% /md %}}</dd>

    <dt class="property-optional"
            title="Optional">
        <span>Private<wbr>Ips</span>
        <span class="property-indicator"></span>
        <span class="property-type">[]string</span>
    </dt>
    <dd>{{% md %}}{{% /md %}}</dd>

    <dt class="property-optional"
            title="Optional">
        <span>Product</span>
        <span class="property-indicator"></span>
        <span class="property-type">*string</span>
    </dt>
    <dd>{{% md %}}Operation system type. Valid values: `"Linux/UNIX"`, `"SUSE Linux"`, `"Windows"`. 
For EC2 Classic instances:  `"Linux/UNIX (Amazon VPC)"`, `"SUSE Linux (Amazon VPC)"`, `"Windows (Amazon VPC)"`.
{{% /md %}}</dd>

    <dt class="property-optional"
            title="Optional">
        <span>Region</span>
        <span class="property-indicator"></span>
        <span class="property-type">*string</span>
    </dt>
    <dd>{{% md %}}The AWS region your group will be created in.
Note: This parameter is required if you specify subnets (through subnet_ids). This parameter is optional if you specify Availability Zones (through availability_zones).
{{% /md %}}</dd>

    <dt class="property-optional"
            title="Optional">
        <span>Revert<wbr>To<wbr>Spot</span>
        <span class="property-indicator"></span>
        <span class="property-type"><a href="#elastigroupreverttospot">*Elastigroup<wbr>Revert<wbr>To<wbr>Spot</a></span>
    </dt>
    <dd>{{% md %}}Hold settings for strategy correction – replacing On-Demand for Spot instances. Supported Values: `"never"`, `"always"`, `"timeWindow"`
{{% /md %}}</dd>

    <dt class="property-optional"
            title="Optional">
        <span>Scaling<wbr>Down<wbr>Policies</span>
        <span class="property-indicator"></span>
        <span class="property-type"><a href="#elastigroupscalingdownpolicy">[]Elastigroup<wbr>Scaling<wbr>Down<wbr>Policy</a></span>
    </dt>
    <dd>{{% md %}}{{% /md %}}</dd>

    <dt class="property-optional"
            title="Optional">
        <span>Scaling<wbr>Strategies</span>
        <span class="property-indicator"></span>
        <span class="property-type"><a href="#elastigroupscalingstrategy">[]Elastigroup<wbr>Scaling<wbr>Strategy</a></span>
    </dt>
    <dd>{{% md %}}Set termination policy.
{{% /md %}}</dd>

    <dt class="property-optional"
            title="Optional">
        <span>Scaling<wbr>Target<wbr>Policies</span>
        <span class="property-indicator"></span>
        <span class="property-type"><a href="#elastigroupscalingtargetpolicy">[]Elastigroup<wbr>Scaling<wbr>Target<wbr>Policy</a></span>
    </dt>
    <dd>{{% md %}}{{% /md %}}</dd>

    <dt class="property-optional"
            title="Optional">
        <span>Scaling<wbr>Up<wbr>Policies</span>
        <span class="property-indicator"></span>
        <span class="property-type"><a href="#elastigroupscalinguppolicy">[]Elastigroup<wbr>Scaling<wbr>Up<wbr>Policy</a></span>
    </dt>
    <dd>{{% md %}}{{% /md %}}</dd>

    <dt class="property-optional"
            title="Optional">
        <span>Scheduled<wbr>Tasks</span>
        <span class="property-indicator"></span>
        <span class="property-type"><a href="#elastigroupscheduledtask">[]Elastigroup<wbr>Scheduled<wbr>Task</a></span>
    </dt>
    <dd>{{% md %}}{{% /md %}}</dd>

    <dt class="property-optional"
            title="Optional">
        <span>Security<wbr>Groups</span>
        <span class="property-indicator"></span>
        <span class="property-type">[]string</span>
    </dt>
    <dd>{{% md %}}A list of associated security group IDS.
{{% /md %}}</dd>

    <dt class="property-optional"
            title="Optional">
        <span>Shutdown<wbr>Script</span>
        <span class="property-indicator"></span>
        <span class="property-type">*string</span>
    </dt>
    <dd>{{% md %}}The Base64-encoded shutdown script that executes prior to instance termination, for more information please see: [Shutdown Script](https://api.spotinst.com/integration-docs/elastigroup/concepts/compute-concepts/shutdown-scripts/)
{{% /md %}}</dd>

    <dt class="property-optional"
            title="Optional">
        <span>Signals</span>
        <span class="property-indicator"></span>
        <span class="property-type"><a href="#elastigroupsignal">[]Elastigroup<wbr>Signal</a></span>
    </dt>
    <dd>{{% md %}}{{% /md %}}</dd>

    <dt class="property-optional"
            title="Optional">
        <span>Spot<wbr>Percentage</span>
        <span class="property-indicator"></span>
        <span class="property-type">*float64</span>
    </dt>
    <dd>{{% md %}}The percentage of Spot instances that would spin up from the `desired_capacity` number.
{{% /md %}}</dd>

    <dt class="property-optional"
            title="Optional">
        <span>Stateful<wbr>Deallocation</span>
        <span class="property-indicator"></span>
        <span class="property-type"><a href="#elastigroupstatefuldeallocation">*Elastigroup<wbr>Stateful<wbr>Deallocation</a></span>
    </dt>
    <dd>{{% md %}}{{% /md %}}</dd>

    <dt class="property-optional"
            title="Optional">
        <span>Subnet<wbr>Ids</span>
        <span class="property-indicator"></span>
        <span class="property-type">[]string</span>
    </dt>
    <dd>{{% md %}}List of Strings of subnet identifiers.
Note: When this parameter is set, `availability_zones` should be left unused.
{{% /md %}}</dd>

    <dt class="property-optional"
            title="Optional">
        <span>Tags</span>
        <span class="property-indicator"></span>
        <span class="property-type"><a href="#elastigrouptag">[]Elastigroup<wbr>Tag</a></span>
    </dt>
    <dd>{{% md %}}A key/value mapping of tags to assign to the resource.
{{% /md %}}</dd>

    <dt class="property-optional"
            title="Optional">
        <span>Target<wbr>Group<wbr>Arns</span>
        <span class="property-indicator"></span>
        <span class="property-type">[]string</span>
    </dt>
    <dd>{{% md %}}{{% /md %}}</dd>

    <dt class="property-optional"
            title="Optional">
        <span>Update<wbr>Policy</span>
        <span class="property-indicator"></span>
        <span class="property-type"><a href="#elastigroupupdatepolicy">*Elastigroup<wbr>Update<wbr>Policy</a></span>
    </dt>
    <dd>{{% md %}}{{% /md %}}</dd>

    <dt class="property-optional"
            title="Optional">
        <span>User<wbr>Data</span>
        <span class="property-indicator"></span>
        <span class="property-type">*string</span>
    </dt>
    <dd>{{% md %}}The user data to provide when launching the instance.
{{% /md %}}</dd>

    <dt class="property-optional"
            title="Optional">
        <span>Utilize<wbr>Reserved<wbr>Instances</span>
        <span class="property-indicator"></span>
        <span class="property-type">*bool</span>
    </dt>
    <dd>{{% md %}}In a case of any available reserved instances, Elastigroup will utilize them first before purchasing Spot instances.
{{% /md %}}</dd>

    <dt class="property-optional"
            title="Optional">
        <span>Wait<wbr>For<wbr>Capacity</span>
        <span class="property-indicator"></span>
        <span class="property-type">*int</span>
    </dt>
    <dd>{{% md %}}Minimum number of instances in a 'HEALTHY' status that is required before continuing. This is ignored when updating with blue/green deployment. Cannot exceed `desired_capacity`.
{{% /md %}}</dd>

    <dt class="property-optional"
            title="Optional">
        <span>Wait<wbr>For<wbr>Capacity<wbr>Timeout</span>
        <span class="property-indicator"></span>
        <span class="property-type">*int</span>
    </dt>
    <dd>{{% md %}}Time (seconds) to wait for instances to report a 'HEALTHY' status. Useful for plans with multiple dependencies that take some time to initialize. Leave undefined or set to `0` to indicate no wait. This is ignored when updating with blue/green deployment. 
{{% /md %}}</dd>

</dl>
{{% /choosable %}}


{{% choosable language nodejs %}}
<dl class="resources-properties">

    <dt class="property-optional"
            title="Optional">
        <span>availability<wbr>Zones</span>
        <span class="property-indicator"></span>
        <span class="property-type">string[]?</span>
    </dt>
    <dd>{{% md %}}List of Strings of availability zones. When this parameter is set, `subnet_ids` should be left unused.
Note: `availability_zones` naming syntax follows the convention `availability-zone:subnet:placement-group-name`. For example, to set an AZ in `us-east-1` with subnet `subnet-123456` and placement group `ClusterI03`, you would set:
`availability_zones = ["us-east-1a:subnet-123456:ClusterI03"]`
{{% /md %}}</dd>

    <dt class="property-optional"
            title="Optional">
        <span>block<wbr>Devices<wbr>Mode</span>
        <span class="property-indicator"></span>
        <span class="property-type">string?</span>
    </dt>
    <dd>{{% md %}}{{% /md %}}</dd>

    <dt class="property-optional"
            title="Optional">
        <span>capacity<wbr>Unit</span>
        <span class="property-indicator"></span>
        <span class="property-type">string?</span>
    </dt>
    <dd>{{% md %}}The capacity unit to launch instances by. If not specified, when choosing the weight unit, each instance will weight as the number of its vCPUs.
{{% /md %}}</dd>

    <dt class="property-optional"
            title="Optional">
        <span>cpu<wbr>Credits</span>
        <span class="property-indicator"></span>
        <span class="property-type">string?</span>
    </dt>
    <dd>{{% md %}}Controls how T3 instances are launched. Valid values: `standard`, `unlimited`.
{{% /md %}}</dd>

    <dt class="property-optional"
            title="Optional">
        <span>description</span>
        <span class="property-indicator"></span>
        <span class="property-type">string?</span>
    </dt>
    <dd>{{% md %}}The group description.
{{% /md %}}</dd>

    <dt class="property-optional"
            title="Optional">
        <span>desired<wbr>Capacity</span>
        <span class="property-indicator"></span>
        <span class="property-type">number?</span>
    </dt>
    <dd>{{% md %}}The desired number of instances the group should have at any time.
{{% /md %}}</dd>

    <dt class="property-optional"
            title="Optional">
        <span>draining<wbr>Timeout</span>
        <span class="property-indicator"></span>
        <span class="property-type">number?</span>
    </dt>
    <dd>{{% md %}}The time in seconds, the instance is allowed to run while detached from the ELB. This is to allow the instance time to be drained from incoming TCP connections before terminating it, during a scale down operation.
{{% /md %}}</dd>

    <dt class="property-optional"
            title="Optional">
        <span>ebs<wbr>Block<wbr>Devices</span>
        <span class="property-indicator"></span>
        <span class="property-type"><a href="#elastigroupebsblockdevice">Elastigroup<wbr>Ebs<wbr>Block<wbr>Device[]?</a></span>
    </dt>
    <dd>{{% md %}}{{% /md %}}</dd>

    <dt class="property-optional"
            title="Optional">
        <span>ebs<wbr>Optimized</span>
        <span class="property-indicator"></span>
        <span class="property-type">boolean?</span>
    </dt>
    <dd>{{% md %}}Enable high bandwidth connectivity between instances and AWS’s Elastic Block Store (EBS). For instance types that are EBS-optimized by default this parameter will be ignored.
{{% /md %}}</dd>

    <dt class="property-optional"
            title="Optional">
        <span>elastic<wbr>Ips</span>
        <span class="property-indicator"></span>
        <span class="property-type">string[]?</span>
    </dt>
    <dd>{{% md %}}A list of [AWS Elastic IP](http://docs.aws.amazon.com/AWSEC2/latest/UserGuide/elastic-ip-addresses-eip.html) allocation IDs to associate to the group instances.
{{% /md %}}</dd>

    <dt class="property-optional"
            title="Optional">
        <span>elastic<wbr>Load<wbr>Balancers</span>
        <span class="property-indicator"></span>
        <span class="property-type">string[]?</span>
    </dt>
    <dd>{{% md %}}{{% /md %}}</dd>

    <dt class="property-optional"
            title="Optional">
        <span>enable<wbr>Monitoring</span>
        <span class="property-indicator"></span>
        <span class="property-type">boolean?</span>
    </dt>
    <dd>{{% md %}}Indicates whether monitoring is enabled for the instance.
{{% /md %}}</dd>

    <dt class="property-optional"
            title="Optional">
        <span>ephemeral<wbr>Block<wbr>Devices</span>
        <span class="property-indicator"></span>
        <span class="property-type"><a href="#elastigroupephemeralblockdevice">Elastigroup<wbr>Ephemeral<wbr>Block<wbr>Device[]?</a></span>
    </dt>
    <dd>{{% md %}}{{% /md %}}</dd>

    <dt class="property-optional"
            title="Optional">
        <span>fallback<wbr>To<wbr>Ondemand</span>
        <span class="property-indicator"></span>
        <span class="property-type">boolean?</span>
    </dt>
    <dd>{{% md %}}In a case of no Spot instances available, Elastigroup will launch on-demand instances instead.
{{% /md %}}</dd>

    <dt class="property-optional"
            title="Optional">
        <span>health<wbr>Check<wbr>Grace<wbr>Period</span>
        <span class="property-indicator"></span>
        <span class="property-type">number?</span>
    </dt>
    <dd>{{% md %}}The amount of time, in seconds, after the instance has launched to starts and check its health.
{{% /md %}}</dd>

    <dt class="property-optional"
            title="Optional">
        <span>health<wbr>Check<wbr>Type</span>
        <span class="property-indicator"></span>
        <span class="property-type">string?</span>
    </dt>
    <dd>{{% md %}}The service that will perform health checks for the instance. Valid values: `"ELB"`, `"HCS"`, `"TARGET_GROUP"`, `"MLB"`, `"EC2"`, `"MULTAI_TARGET_SET"`, `"MLB_RUNTIME"`, `"K8S_NODE"`, `"NOMAD_NODE"`, `"ECS_CLUSTER_INSTANCE"`.
{{% /md %}}</dd>

    <dt class="property-optional"
            title="Optional">
        <span>health<wbr>Check<wbr>Unhealthy<wbr>Duration<wbr>Before<wbr>Replacement</span>
        <span class="property-indicator"></span>
        <span class="property-type">number?</span>
    </dt>
    <dd>{{% md %}}The amount of time, in seconds, that we will wait before replacing an instance that is running and became unhealthy (this is only applicable for instances that were once healthy).
{{% /md %}}</dd>

    <dt class="property-optional"
            title="Optional">
        <span>iam<wbr>Instance<wbr>Profile</span>
        <span class="property-indicator"></span>
        <span class="property-type">string?</span>
    </dt>
    <dd>{{% md %}}The ARN or name of an IAM instance profile to associate with launched instances.
{{% /md %}}</dd>

    <dt class="property-optional"
            title="Optional">
        <span>image<wbr>Id</span>
        <span class="property-indicator"></span>
        <span class="property-type">string?</span>
    </dt>
    <dd>{{% md %}}The ID of the AMI used to launch the instance.
{{% /md %}}</dd>

    <dt class="property-optional"
            title="Optional">
        <span>instance<wbr>Types<wbr>Ondemand</span>
        <span class="property-indicator"></span>
        <span class="property-type">string?</span>
    </dt>
    <dd>{{% md %}}The type of instance determines your instance's CPU capacity, memory and storage (e.g., m1.small, c1.xlarge).
{{% /md %}}</dd>

    <dt class="property-optional"
            title="Optional">
        <span>instance<wbr>Types<wbr>Preferred<wbr>Spots</span>
        <span class="property-indicator"></span>
        <span class="property-type">string[]?</span>
    </dt>
    <dd>{{% md %}}Prioritize a subset of spot instance types. Must be a subset of the selected spot instance types.
{{% /md %}}</dd>

    <dt class="property-optional"
            title="Optional">
        <span>instance<wbr>Types<wbr>Spots</span>
        <span class="property-indicator"></span>
        <span class="property-type">string[]?</span>
    </dt>
    <dd>{{% md %}}One or more instance types.
{{% /md %}}</dd>

    <dt class="property-optional"
            title="Optional">
        <span>instance<wbr>Types<wbr>Weights</span>
        <span class="property-indicator"></span>
        <span class="property-type"><a href="#elastigroupinstancetypesweight">Elastigroup<wbr>Instance<wbr>Types<wbr>Weight[]?</a></span>
    </dt>
    <dd>{{% md %}}List of weights per instance type for weighted groups. Each object in the list should have the following attributes:
{{% /md %}}</dd>

    <dt class="property-optional"
            title="Optional">
        <span>integration<wbr>Beanstalk</span>
        <span class="property-indicator"></span>
        <span class="property-type"><a href="#elastigroupintegrationbeanstalk">Elastigroup<wbr>Integration<wbr>Beanstalk?</a></span>
    </dt>
    <dd>{{% md %}}{{% /md %}}</dd>

    <dt class="property-optional"
            title="Optional">
        <span>integration<wbr>Codedeploy</span>
        <span class="property-indicator"></span>
        <span class="property-type"><a href="#elastigroupintegrationcodedeploy">Elastigroup<wbr>Integration<wbr>Codedeploy?</a></span>
    </dt>
    <dd>{{% md %}}{{% /md %}}</dd>

    <dt class="property-optional"
            title="Optional">
        <span>integration<wbr>Docker<wbr>Swarm</span>
        <span class="property-indicator"></span>
        <span class="property-type"><a href="#elastigroupintegrationdockerswarm">Elastigroup<wbr>Integration<wbr>Docker<wbr>Swarm?</a></span>
    </dt>
    <dd>{{% md %}}{{% /md %}}</dd>

    <dt class="property-optional"
            title="Optional">
        <span>integration<wbr>Ecs</span>
        <span class="property-indicator"></span>
        <span class="property-type"><a href="#elastigroupintegrationecs">Elastigroup<wbr>Integration<wbr>Ecs?</a></span>
    </dt>
    <dd>{{% md %}}{{% /md %}}</dd>

    <dt class="property-optional"
            title="Optional">
        <span>integration<wbr>Gitlab</span>
        <span class="property-indicator"></span>
        <span class="property-type"><a href="#elastigroupintegrationgitlab">Elastigroup<wbr>Integration<wbr>Gitlab?</a></span>
    </dt>
    <dd>{{% md %}}{{% /md %}}</dd>

    <dt class="property-optional"
            title="Optional">
        <span>integration<wbr>Kubernetes</span>
        <span class="property-indicator"></span>
        <span class="property-type"><a href="#elastigroupintegrationkubernetes">Elastigroup<wbr>Integration<wbr>Kubernetes?</a></span>
    </dt>
    <dd>{{% md %}}{{% /md %}}</dd>

    <dt class="property-optional"
            title="Optional">
        <span>integration<wbr>Mesosphere</span>
        <span class="property-indicator"></span>
        <span class="property-type"><a href="#elastigroupintegrationmesosphere">Elastigroup<wbr>Integration<wbr>Mesosphere?</a></span>
    </dt>
    <dd>{{% md %}}{{% /md %}}</dd>

    <dt class="property-optional"
            title="Optional">
        <span>integration<wbr>Multai<wbr>Runtime</span>
        <span class="property-indicator"></span>
        <span class="property-type"><a href="#elastigroupintegrationmultairuntime">Elastigroup<wbr>Integration<wbr>Multai<wbr>Runtime?</a></span>
    </dt>
    <dd>{{% md %}}{{% /md %}}</dd>

    <dt class="property-optional"
            title="Optional">
        <span>integration<wbr>Nomad</span>
        <span class="property-indicator"></span>
        <span class="property-type"><a href="#elastigroupintegrationnomad">Elastigroup<wbr>Integration<wbr>Nomad?</a></span>
    </dt>
    <dd>{{% md %}}{{% /md %}}</dd>

    <dt class="property-optional"
            title="Optional">
        <span>integration<wbr>Rancher</span>
        <span class="property-indicator"></span>
        <span class="property-type"><a href="#elastigroupintegrationrancher">Elastigroup<wbr>Integration<wbr>Rancher?</a></span>
    </dt>
    <dd>{{% md %}}{{% /md %}}</dd>

    <dt class="property-optional"
            title="Optional">
        <span>integration<wbr>Route53</span>
        <span class="property-indicator"></span>
        <span class="property-type"><a href="#elastigroupintegrationroute53">Elastigroup<wbr>Integration<wbr>Route53?</a></span>
    </dt>
    <dd>{{% md %}}{{% /md %}}</dd>

    <dt class="property-optional"
            title="Optional">
        <span>key<wbr>Name</span>
        <span class="property-indicator"></span>
        <span class="property-type">string?</span>
    </dt>
    <dd>{{% md %}}The key name that should be used for the instance.
{{% /md %}}</dd>

    <dt class="property-optional"
            title="Optional">
        <span>lifetime<wbr>Period</span>
        <span class="property-indicator"></span>
        <span class="property-type">string?</span>
    </dt>
    <dd>{{% md %}}{{% /md %}}</dd>

    <dt class="property-optional"
            title="Optional">
        <span>max<wbr>Size</span>
        <span class="property-indicator"></span>
        <span class="property-type">number?</span>
    </dt>
    <dd>{{% md %}}The maximum number of instances the group should have at any time.
{{% /md %}}</dd>

    <dt class="property-optional"
            title="Optional">
        <span>min<wbr>Size</span>
        <span class="property-indicator"></span>
        <span class="property-type">number?</span>
    </dt>
    <dd>{{% md %}}The minimum number of instances the group should have at any time.
{{% /md %}}</dd>

    <dt class="property-optional"
            title="Optional">
        <span>multai<wbr>Target<wbr>Sets</span>
        <span class="property-indicator"></span>
        <span class="property-type"><a href="#elastigroupmultaitargetset">Elastigroup<wbr>Multai<wbr>Target<wbr>Set[]?</a></span>
    </dt>
    <dd>{{% md %}}{{% /md %}}</dd>

    <dt class="property-optional"
            title="Optional">
        <span>name</span>
        <span class="property-indicator"></span>
        <span class="property-type">string?</span>
    </dt>
    <dd>{{% md %}}The group name.
{{% /md %}}</dd>

    <dt class="property-optional"
            title="Optional">
        <span>network<wbr>Interfaces</span>
        <span class="property-indicator"></span>
        <span class="property-type"><a href="#elastigroupnetworkinterface">Elastigroup<wbr>Network<wbr>Interface[]?</a></span>
    </dt>
    <dd>{{% md %}}{{% /md %}}</dd>

    <dt class="property-optional"
            title="Optional">
        <span>ondemand<wbr>Count</span>
        <span class="property-indicator"></span>
        <span class="property-type">number?</span>
    </dt>
    <dd>{{% md %}}Number of on demand instances to launch in the group. All other instances will be spot instances. When this parameter is set the `spot_percentage` parameter is being ignored.
{{% /md %}}</dd>

    <dt class="property-optional"
            title="Optional">
        <span>orientation</span>
        <span class="property-indicator"></span>
        <span class="property-type">string?</span>
    </dt>
    <dd>{{% md %}}Select a prediction strategy. Valid values: `"balanced"`, `"costOriented"`, `"equalAzDistribution"`, `"availabilityOriented"`.    
{{% /md %}}</dd>

    <dt class="property-optional"
            title="Optional">
        <span>persist<wbr>Block<wbr>Devices</span>
        <span class="property-indicator"></span>
        <span class="property-type">boolean?</span>
    </dt>
    <dd>{{% md %}}{{% /md %}}</dd>

    <dt class="property-optional"
            title="Optional">
        <span>persist<wbr>Private<wbr>Ip</span>
        <span class="property-indicator"></span>
        <span class="property-type">boolean?</span>
    </dt>
    <dd>{{% md %}}{{% /md %}}</dd>

    <dt class="property-optional"
            title="Optional">
        <span>persist<wbr>Root<wbr>Device</span>
        <span class="property-indicator"></span>
        <span class="property-type">boolean?</span>
    </dt>
    <dd>{{% md %}}{{% /md %}}</dd>

    <dt class="property-optional"
            title="Optional">
        <span>placement<wbr>Tenancy</span>
        <span class="property-indicator"></span>
        <span class="property-type">string?</span>
    </dt>
    <dd>{{% md %}}Enable dedicated tenancy. Note: There is a flat hourly fee for each region in which dedicated tenancy is used.
{{% /md %}}</dd>

    <dt class="property-optional"
            title="Optional">
        <span>preferred<wbr>Availability<wbr>Zones</span>
        <span class="property-indicator"></span>
        <span class="property-type">string[]?</span>
    </dt>
    <dd>{{% md %}}The AZs to prioritize when launching Spot instances. If no markets are available in the Preferred AZs, Spot instances are launched in the non-preferred AZs. 
Note: Must be a sublist of `availability_zones` and `orientation` value must not be `"equalAzDistribution"`.
{{% /md %}}</dd>

    <dt class="property-optional"
            title="Optional">
        <span>private<wbr>Ips</span>
        <span class="property-indicator"></span>
        <span class="property-type">string[]?</span>
    </dt>
    <dd>{{% md %}}{{% /md %}}</dd>

    <dt class="property-optional"
            title="Optional">
        <span>product</span>
        <span class="property-indicator"></span>
        <span class="property-type">string?</span>
    </dt>
    <dd>{{% md %}}Operation system type. Valid values: `"Linux/UNIX"`, `"SUSE Linux"`, `"Windows"`. 
For EC2 Classic instances:  `"Linux/UNIX (Amazon VPC)"`, `"SUSE Linux (Amazon VPC)"`, `"Windows (Amazon VPC)"`.
{{% /md %}}</dd>

    <dt class="property-optional"
            title="Optional">
        <span>region</span>
        <span class="property-indicator"></span>
        <span class="property-type">string?</span>
    </dt>
    <dd>{{% md %}}The AWS region your group will be created in.
Note: This parameter is required if you specify subnets (through subnet_ids). This parameter is optional if you specify Availability Zones (through availability_zones).
{{% /md %}}</dd>

    <dt class="property-optional"
            title="Optional">
        <span>revert<wbr>To<wbr>Spot</span>
        <span class="property-indicator"></span>
        <span class="property-type"><a href="#elastigroupreverttospot">Elastigroup<wbr>Revert<wbr>To<wbr>Spot?</a></span>
    </dt>
    <dd>{{% md %}}Hold settings for strategy correction – replacing On-Demand for Spot instances. Supported Values: `"never"`, `"always"`, `"timeWindow"`
{{% /md %}}</dd>

    <dt class="property-optional"
            title="Optional">
        <span>scaling<wbr>Down<wbr>Policies</span>
        <span class="property-indicator"></span>
        <span class="property-type"><a href="#elastigroupscalingdownpolicy">Elastigroup<wbr>Scaling<wbr>Down<wbr>Policy[]?</a></span>
    </dt>
    <dd>{{% md %}}{{% /md %}}</dd>

    <dt class="property-optional"
            title="Optional">
        <span>scaling<wbr>Strategies</span>
        <span class="property-indicator"></span>
        <span class="property-type"><a href="#elastigroupscalingstrategy">Elastigroup<wbr>Scaling<wbr>Strategy[]?</a></span>
    </dt>
    <dd>{{% md %}}Set termination policy.
{{% /md %}}</dd>

    <dt class="property-optional"
            title="Optional">
        <span>scaling<wbr>Target<wbr>Policies</span>
        <span class="property-indicator"></span>
        <span class="property-type"><a href="#elastigroupscalingtargetpolicy">Elastigroup<wbr>Scaling<wbr>Target<wbr>Policy[]?</a></span>
    </dt>
    <dd>{{% md %}}{{% /md %}}</dd>

    <dt class="property-optional"
            title="Optional">
        <span>scaling<wbr>Up<wbr>Policies</span>
        <span class="property-indicator"></span>
        <span class="property-type"><a href="#elastigroupscalinguppolicy">Elastigroup<wbr>Scaling<wbr>Up<wbr>Policy[]?</a></span>
    </dt>
    <dd>{{% md %}}{{% /md %}}</dd>

    <dt class="property-optional"
            title="Optional">
        <span>scheduled<wbr>Tasks</span>
        <span class="property-indicator"></span>
        <span class="property-type"><a href="#elastigroupscheduledtask">Elastigroup<wbr>Scheduled<wbr>Task[]?</a></span>
    </dt>
    <dd>{{% md %}}{{% /md %}}</dd>

    <dt class="property-optional"
            title="Optional">
        <span>security<wbr>Groups</span>
        <span class="property-indicator"></span>
        <span class="property-type">string[]?</span>
    </dt>
    <dd>{{% md %}}A list of associated security group IDS.
{{% /md %}}</dd>

    <dt class="property-optional"
            title="Optional">
        <span>shutdown<wbr>Script</span>
        <span class="property-indicator"></span>
        <span class="property-type">string?</span>
    </dt>
    <dd>{{% md %}}The Base64-encoded shutdown script that executes prior to instance termination, for more information please see: [Shutdown Script](https://api.spotinst.com/integration-docs/elastigroup/concepts/compute-concepts/shutdown-scripts/)
{{% /md %}}</dd>

    <dt class="property-optional"
            title="Optional">
        <span>signals</span>
        <span class="property-indicator"></span>
        <span class="property-type"><a href="#elastigroupsignal">Elastigroup<wbr>Signal[]?</a></span>
    </dt>
    <dd>{{% md %}}{{% /md %}}</dd>

    <dt class="property-optional"
            title="Optional">
        <span>spot<wbr>Percentage</span>
        <span class="property-indicator"></span>
        <span class="property-type">number?</span>
    </dt>
    <dd>{{% md %}}The percentage of Spot instances that would spin up from the `desired_capacity` number.
{{% /md %}}</dd>

    <dt class="property-optional"
            title="Optional">
        <span>stateful<wbr>Deallocation</span>
        <span class="property-indicator"></span>
        <span class="property-type"><a href="#elastigroupstatefuldeallocation">Elastigroup<wbr>Stateful<wbr>Deallocation?</a></span>
    </dt>
    <dd>{{% md %}}{{% /md %}}</dd>

    <dt class="property-optional"
            title="Optional">
        <span>subnet<wbr>Ids</span>
        <span class="property-indicator"></span>
        <span class="property-type">string[]?</span>
    </dt>
    <dd>{{% md %}}List of Strings of subnet identifiers.
Note: When this parameter is set, `availability_zones` should be left unused.
{{% /md %}}</dd>

    <dt class="property-optional"
            title="Optional">
        <span>tags</span>
        <span class="property-indicator"></span>
        <span class="property-type"><a href="#elastigrouptag">Elastigroup<wbr>Tag[]?</a></span>
    </dt>
    <dd>{{% md %}}A key/value mapping of tags to assign to the resource.
{{% /md %}}</dd>

    <dt class="property-optional"
            title="Optional">
        <span>target<wbr>Group<wbr>Arns</span>
        <span class="property-indicator"></span>
        <span class="property-type">string[]?</span>
    </dt>
    <dd>{{% md %}}{{% /md %}}</dd>

    <dt class="property-optional"
            title="Optional">
        <span>update<wbr>Policy</span>
        <span class="property-indicator"></span>
        <span class="property-type"><a href="#elastigroupupdatepolicy">Elastigroup<wbr>Update<wbr>Policy?</a></span>
    </dt>
    <dd>{{% md %}}{{% /md %}}</dd>

    <dt class="property-optional"
            title="Optional">
        <span>user<wbr>Data</span>
        <span class="property-indicator"></span>
        <span class="property-type">string?</span>
    </dt>
    <dd>{{% md %}}The user data to provide when launching the instance.
{{% /md %}}</dd>

    <dt class="property-optional"
            title="Optional">
        <span>utilize<wbr>Reserved<wbr>Instances</span>
        <span class="property-indicator"></span>
        <span class="property-type">boolean?</span>
    </dt>
    <dd>{{% md %}}In a case of any available reserved instances, Elastigroup will utilize them first before purchasing Spot instances.
{{% /md %}}</dd>

    <dt class="property-optional"
            title="Optional">
        <span>wait<wbr>For<wbr>Capacity</span>
        <span class="property-indicator"></span>
        <span class="property-type">number?</span>
    </dt>
    <dd>{{% md %}}Minimum number of instances in a 'HEALTHY' status that is required before continuing. This is ignored when updating with blue/green deployment. Cannot exceed `desired_capacity`.
{{% /md %}}</dd>

    <dt class="property-optional"
            title="Optional">
        <span>wait<wbr>For<wbr>Capacity<wbr>Timeout</span>
        <span class="property-indicator"></span>
        <span class="property-type">number?</span>
    </dt>
    <dd>{{% md %}}Time (seconds) to wait for instances to report a 'HEALTHY' status. Useful for plans with multiple dependencies that take some time to initialize. Leave undefined or set to `0` to indicate no wait. This is ignored when updating with blue/green deployment. 
{{% /md %}}</dd>

</dl>
{{% /choosable %}}


{{% choosable language python %}}
<dl class="resources-properties">

    <dt class="property-optional"
            title="Optional">
        <span>availability_<wbr>zones</span>
        <span class="property-indicator"></span>
        <span class="property-type">List[str]</span>
    </dt>
    <dd>{{% md %}}List of Strings of availability zones. When this parameter is set, `subnet_ids` should be left unused.
Note: `availability_zones` naming syntax follows the convention `availability-zone:subnet:placement-group-name`. For example, to set an AZ in `us-east-1` with subnet `subnet-123456` and placement group `ClusterI03`, you would set:
`availability_zones = ["us-east-1a:subnet-123456:ClusterI03"]`
{{% /md %}}</dd>

    <dt class="property-optional"
            title="Optional">
        <span>block_<wbr>devices_<wbr>mode</span>
        <span class="property-indicator"></span>
        <span class="property-type">str</span>
    </dt>
    <dd>{{% md %}}{{% /md %}}</dd>

    <dt class="property-optional"
            title="Optional">
        <span>capacity_<wbr>unit</span>
        <span class="property-indicator"></span>
        <span class="property-type">str</span>
    </dt>
    <dd>{{% md %}}The capacity unit to launch instances by. If not specified, when choosing the weight unit, each instance will weight as the number of its vCPUs.
{{% /md %}}</dd>

    <dt class="property-optional"
            title="Optional">
        <span>cpu_<wbr>credits</span>
        <span class="property-indicator"></span>
        <span class="property-type">str</span>
    </dt>
    <dd>{{% md %}}Controls how T3 instances are launched. Valid values: `standard`, `unlimited`.
{{% /md %}}</dd>

    <dt class="property-optional"
            title="Optional">
        <span>description</span>
        <span class="property-indicator"></span>
        <span class="property-type">str</span>
    </dt>
    <dd>{{% md %}}The group description.
{{% /md %}}</dd>

    <dt class="property-optional"
            title="Optional">
        <span>desired_<wbr>capacity</span>
        <span class="property-indicator"></span>
        <span class="property-type">float</span>
    </dt>
    <dd>{{% md %}}The desired number of instances the group should have at any time.
{{% /md %}}</dd>

    <dt class="property-optional"
            title="Optional">
        <span>draining_<wbr>timeout</span>
        <span class="property-indicator"></span>
        <span class="property-type">float</span>
    </dt>
    <dd>{{% md %}}The time in seconds, the instance is allowed to run while detached from the ELB. This is to allow the instance time to be drained from incoming TCP connections before terminating it, during a scale down operation.
{{% /md %}}</dd>

    <dt class="property-optional"
            title="Optional">
        <span>ebs_<wbr>block_<wbr>devices</span>
        <span class="property-indicator"></span>
        <span class="property-type"><a href="#elastigroupebsblockdevice">List[Elastigroup<wbr>Ebs<wbr>Block<wbr>Device]</a></span>
    </dt>
    <dd>{{% md %}}{{% /md %}}</dd>

    <dt class="property-optional"
            title="Optional">
        <span>ebs_<wbr>optimized</span>
        <span class="property-indicator"></span>
        <span class="property-type">bool</span>
    </dt>
    <dd>{{% md %}}Enable high bandwidth connectivity between instances and AWS’s Elastic Block Store (EBS). For instance types that are EBS-optimized by default this parameter will be ignored.
{{% /md %}}</dd>

    <dt class="property-optional"
            title="Optional">
        <span>elastic_<wbr>ips</span>
        <span class="property-indicator"></span>
        <span class="property-type">List[str]</span>
    </dt>
    <dd>{{% md %}}A list of [AWS Elastic IP](http://docs.aws.amazon.com/AWSEC2/latest/UserGuide/elastic-ip-addresses-eip.html) allocation IDs to associate to the group instances.
{{% /md %}}</dd>

    <dt class="property-optional"
            title="Optional">
        <span>elastic_<wbr>load_<wbr>balancers</span>
        <span class="property-indicator"></span>
        <span class="property-type">List[str]</span>
    </dt>
    <dd>{{% md %}}{{% /md %}}</dd>

    <dt class="property-optional"
            title="Optional">
        <span>enable_<wbr>monitoring</span>
        <span class="property-indicator"></span>
        <span class="property-type">bool</span>
    </dt>
    <dd>{{% md %}}Indicates whether monitoring is enabled for the instance.
{{% /md %}}</dd>

    <dt class="property-optional"
            title="Optional">
        <span>ephemeral_<wbr>block_<wbr>devices</span>
        <span class="property-indicator"></span>
        <span class="property-type"><a href="#elastigroupephemeralblockdevice">List[Elastigroup<wbr>Ephemeral<wbr>Block<wbr>Device]</a></span>
    </dt>
    <dd>{{% md %}}{{% /md %}}</dd>

    <dt class="property-optional"
            title="Optional">
        <span>fallback_<wbr>to_<wbr>ondemand</span>
        <span class="property-indicator"></span>
        <span class="property-type">bool</span>
    </dt>
    <dd>{{% md %}}In a case of no Spot instances available, Elastigroup will launch on-demand instances instead.
{{% /md %}}</dd>

    <dt class="property-optional"
            title="Optional">
        <span>health_<wbr>check_<wbr>grace_<wbr>period</span>
        <span class="property-indicator"></span>
        <span class="property-type">float</span>
    </dt>
    <dd>{{% md %}}The amount of time, in seconds, after the instance has launched to starts and check its health.
{{% /md %}}</dd>

    <dt class="property-optional"
            title="Optional">
        <span>health_<wbr>check_<wbr>type</span>
        <span class="property-indicator"></span>
        <span class="property-type">str</span>
    </dt>
    <dd>{{% md %}}The service that will perform health checks for the instance. Valid values: `"ELB"`, `"HCS"`, `"TARGET_GROUP"`, `"MLB"`, `"EC2"`, `"MULTAI_TARGET_SET"`, `"MLB_RUNTIME"`, `"K8S_NODE"`, `"NOMAD_NODE"`, `"ECS_CLUSTER_INSTANCE"`.
{{% /md %}}</dd>

    <dt class="property-optional"
            title="Optional">
        <span>health_<wbr>check_<wbr>unhealthy_<wbr>duration_<wbr>before_<wbr>replacement</span>
        <span class="property-indicator"></span>
        <span class="property-type">float</span>
    </dt>
    <dd>{{% md %}}The amount of time, in seconds, that we will wait before replacing an instance that is running and became unhealthy (this is only applicable for instances that were once healthy).
{{% /md %}}</dd>

    <dt class="property-optional"
            title="Optional">
        <span>iam_<wbr>instance_<wbr>profile</span>
        <span class="property-indicator"></span>
        <span class="property-type">str</span>
    </dt>
    <dd>{{% md %}}The ARN or name of an IAM instance profile to associate with launched instances.
{{% /md %}}</dd>

    <dt class="property-optional"
            title="Optional">
        <span>image_<wbr>id</span>
        <span class="property-indicator"></span>
        <span class="property-type">str</span>
    </dt>
    <dd>{{% md %}}The ID of the AMI used to launch the instance.
{{% /md %}}</dd>

    <dt class="property-optional"
            title="Optional">
        <span>instance_<wbr>types_<wbr>ondemand</span>
        <span class="property-indicator"></span>
        <span class="property-type">str</span>
    </dt>
    <dd>{{% md %}}The type of instance determines your instance's CPU capacity, memory and storage (e.g., m1.small, c1.xlarge).
{{% /md %}}</dd>

    <dt class="property-optional"
            title="Optional">
        <span>instance_<wbr>types_<wbr>preferred_<wbr>spots</span>
        <span class="property-indicator"></span>
        <span class="property-type">List[str]</span>
    </dt>
    <dd>{{% md %}}Prioritize a subset of spot instance types. Must be a subset of the selected spot instance types.
{{% /md %}}</dd>

    <dt class="property-optional"
            title="Optional">
        <span>instance_<wbr>types_<wbr>spots</span>
        <span class="property-indicator"></span>
        <span class="property-type">List[str]</span>
    </dt>
    <dd>{{% md %}}One or more instance types.
{{% /md %}}</dd>

    <dt class="property-optional"
            title="Optional">
        <span>instance_<wbr>types_<wbr>weights</span>
        <span class="property-indicator"></span>
        <span class="property-type"><a href="#elastigroupinstancetypesweight">List[Elastigroup<wbr>Instance<wbr>Types<wbr>Weight]</a></span>
    </dt>
    <dd>{{% md %}}List of weights per instance type for weighted groups. Each object in the list should have the following attributes:
{{% /md %}}</dd>

    <dt class="property-optional"
            title="Optional">
        <span>integration_<wbr>beanstalk</span>
        <span class="property-indicator"></span>
        <span class="property-type"><a href="#elastigroupintegrationbeanstalk">Dict[Elastigroup<wbr>Integration<wbr>Beanstalk]</a></span>
    </dt>
    <dd>{{% md %}}{{% /md %}}</dd>

    <dt class="property-optional"
            title="Optional">
        <span>integration_<wbr>codedeploy</span>
        <span class="property-indicator"></span>
        <span class="property-type"><a href="#elastigroupintegrationcodedeploy">Dict[Elastigroup<wbr>Integration<wbr>Codedeploy]</a></span>
    </dt>
    <dd>{{% md %}}{{% /md %}}</dd>

    <dt class="property-optional"
            title="Optional">
        <span>integration_<wbr>docker_<wbr>swarm</span>
        <span class="property-indicator"></span>
        <span class="property-type"><a href="#elastigroupintegrationdockerswarm">Dict[Elastigroup<wbr>Integration<wbr>Docker<wbr>Swarm]</a></span>
    </dt>
    <dd>{{% md %}}{{% /md %}}</dd>

    <dt class="property-optional"
            title="Optional">
        <span>integration_<wbr>ecs</span>
        <span class="property-indicator"></span>
        <span class="property-type"><a href="#elastigroupintegrationecs">Dict[Elastigroup<wbr>Integration<wbr>Ecs]</a></span>
    </dt>
    <dd>{{% md %}}{{% /md %}}</dd>

    <dt class="property-optional"
            title="Optional">
        <span>integration_<wbr>gitlab</span>
        <span class="property-indicator"></span>
        <span class="property-type"><a href="#elastigroupintegrationgitlab">Dict[Elastigroup<wbr>Integration<wbr>Gitlab]</a></span>
    </dt>
    <dd>{{% md %}}{{% /md %}}</dd>

    <dt class="property-optional"
            title="Optional">
        <span>integration_<wbr>kubernetes</span>
        <span class="property-indicator"></span>
        <span class="property-type"><a href="#elastigroupintegrationkubernetes">Dict[Elastigroup<wbr>Integration<wbr>Kubernetes]</a></span>
    </dt>
    <dd>{{% md %}}{{% /md %}}</dd>

    <dt class="property-optional"
            title="Optional">
        <span>integration_<wbr>mesosphere</span>
        <span class="property-indicator"></span>
        <span class="property-type"><a href="#elastigroupintegrationmesosphere">Dict[Elastigroup<wbr>Integration<wbr>Mesosphere]</a></span>
    </dt>
    <dd>{{% md %}}{{% /md %}}</dd>

    <dt class="property-optional"
            title="Optional">
        <span>integration_<wbr>multai_<wbr>runtime</span>
        <span class="property-indicator"></span>
        <span class="property-type"><a href="#elastigroupintegrationmultairuntime">Dict[Elastigroup<wbr>Integration<wbr>Multai<wbr>Runtime]</a></span>
    </dt>
    <dd>{{% md %}}{{% /md %}}</dd>

    <dt class="property-optional"
            title="Optional">
        <span>integration_<wbr>nomad</span>
        <span class="property-indicator"></span>
        <span class="property-type"><a href="#elastigroupintegrationnomad">Dict[Elastigroup<wbr>Integration<wbr>Nomad]</a></span>
    </dt>
    <dd>{{% md %}}{{% /md %}}</dd>

    <dt class="property-optional"
            title="Optional">
        <span>integration_<wbr>rancher</span>
        <span class="property-indicator"></span>
        <span class="property-type"><a href="#elastigroupintegrationrancher">Dict[Elastigroup<wbr>Integration<wbr>Rancher]</a></span>
    </dt>
    <dd>{{% md %}}{{% /md %}}</dd>

    <dt class="property-optional"
            title="Optional">
        <span>integration_<wbr>route53</span>
        <span class="property-indicator"></span>
        <span class="property-type"><a href="#elastigroupintegrationroute53">Dict[Elastigroup<wbr>Integration<wbr>Route53]</a></span>
    </dt>
    <dd>{{% md %}}{{% /md %}}</dd>

    <dt class="property-optional"
            title="Optional">
        <span>key_<wbr>name</span>
        <span class="property-indicator"></span>
        <span class="property-type">str</span>
    </dt>
    <dd>{{% md %}}The key name that should be used for the instance.
{{% /md %}}</dd>

    <dt class="property-optional"
            title="Optional">
        <span>lifetime_<wbr>period</span>
        <span class="property-indicator"></span>
        <span class="property-type">str</span>
    </dt>
    <dd>{{% md %}}{{% /md %}}</dd>

    <dt class="property-optional"
            title="Optional">
        <span>max_<wbr>size</span>
        <span class="property-indicator"></span>
        <span class="property-type">float</span>
    </dt>
    <dd>{{% md %}}The maximum number of instances the group should have at any time.
{{% /md %}}</dd>

    <dt class="property-optional"
            title="Optional">
        <span>min_<wbr>size</span>
        <span class="property-indicator"></span>
        <span class="property-type">float</span>
    </dt>
    <dd>{{% md %}}The minimum number of instances the group should have at any time.
{{% /md %}}</dd>

    <dt class="property-optional"
            title="Optional">
        <span>multai_<wbr>target_<wbr>sets</span>
        <span class="property-indicator"></span>
        <span class="property-type"><a href="#elastigroupmultaitargetset">List[Elastigroup<wbr>Multai<wbr>Target<wbr>Set]</a></span>
    </dt>
    <dd>{{% md %}}{{% /md %}}</dd>

    <dt class="property-optional"
            title="Optional">
        <span>name</span>
        <span class="property-indicator"></span>
        <span class="property-type">str</span>
    </dt>
    <dd>{{% md %}}The group name.
{{% /md %}}</dd>

    <dt class="property-optional"
            title="Optional">
        <span>network_<wbr>interfaces</span>
        <span class="property-indicator"></span>
        <span class="property-type"><a href="#elastigroupnetworkinterface">List[Elastigroup<wbr>Network<wbr>Interface]</a></span>
    </dt>
    <dd>{{% md %}}{{% /md %}}</dd>

    <dt class="property-optional"
            title="Optional">
        <span>ondemand_<wbr>count</span>
        <span class="property-indicator"></span>
        <span class="property-type">float</span>
    </dt>
    <dd>{{% md %}}Number of on demand instances to launch in the group. All other instances will be spot instances. When this parameter is set the `spot_percentage` parameter is being ignored.
{{% /md %}}</dd>

    <dt class="property-optional"
            title="Optional">
        <span>orientation</span>
        <span class="property-indicator"></span>
        <span class="property-type">str</span>
    </dt>
    <dd>{{% md %}}Select a prediction strategy. Valid values: `"balanced"`, `"costOriented"`, `"equalAzDistribution"`, `"availabilityOriented"`.    
{{% /md %}}</dd>

    <dt class="property-optional"
            title="Optional">
        <span>persist_<wbr>block_<wbr>devices</span>
        <span class="property-indicator"></span>
        <span class="property-type">bool</span>
    </dt>
    <dd>{{% md %}}{{% /md %}}</dd>

    <dt class="property-optional"
            title="Optional">
        <span>persist_<wbr>private_<wbr>ip</span>
        <span class="property-indicator"></span>
        <span class="property-type">bool</span>
    </dt>
    <dd>{{% md %}}{{% /md %}}</dd>

    <dt class="property-optional"
            title="Optional">
        <span>persist_<wbr>root_<wbr>device</span>
        <span class="property-indicator"></span>
        <span class="property-type">bool</span>
    </dt>
    <dd>{{% md %}}{{% /md %}}</dd>

    <dt class="property-optional"
            title="Optional">
        <span>placement_<wbr>tenancy</span>
        <span class="property-indicator"></span>
        <span class="property-type">str</span>
    </dt>
    <dd>{{% md %}}Enable dedicated tenancy. Note: There is a flat hourly fee for each region in which dedicated tenancy is used.
{{% /md %}}</dd>

    <dt class="property-optional"
            title="Optional">
        <span>preferred_<wbr>availability_<wbr>zones</span>
        <span class="property-indicator"></span>
        <span class="property-type">List[str]</span>
    </dt>
    <dd>{{% md %}}The AZs to prioritize when launching Spot instances. If no markets are available in the Preferred AZs, Spot instances are launched in the non-preferred AZs. 
Note: Must be a sublist of `availability_zones` and `orientation` value must not be `"equalAzDistribution"`.
{{% /md %}}</dd>

    <dt class="property-optional"
            title="Optional">
        <span>private_<wbr>ips</span>
        <span class="property-indicator"></span>
        <span class="property-type">List[str]</span>
    </dt>
    <dd>{{% md %}}{{% /md %}}</dd>

    <dt class="property-optional"
            title="Optional">
        <span>product</span>
        <span class="property-indicator"></span>
        <span class="property-type">str</span>
    </dt>
    <dd>{{% md %}}Operation system type. Valid values: `"Linux/UNIX"`, `"SUSE Linux"`, `"Windows"`. 
For EC2 Classic instances:  `"Linux/UNIX (Amazon VPC)"`, `"SUSE Linux (Amazon VPC)"`, `"Windows (Amazon VPC)"`.
{{% /md %}}</dd>

    <dt class="property-optional"
            title="Optional">
        <span>region</span>
        <span class="property-indicator"></span>
        <span class="property-type">str</span>
    </dt>
    <dd>{{% md %}}The AWS region your group will be created in.
Note: This parameter is required if you specify subnets (through subnet_ids). This parameter is optional if you specify Availability Zones (through availability_zones).
{{% /md %}}</dd>

    <dt class="property-optional"
            title="Optional">
        <span>revert_<wbr>to_<wbr>spot</span>
        <span class="property-indicator"></span>
        <span class="property-type"><a href="#elastigroupreverttospot">Dict[Elastigroup<wbr>Revert<wbr>To<wbr>Spot]</a></span>
    </dt>
    <dd>{{% md %}}Hold settings for strategy correction – replacing On-Demand for Spot instances. Supported Values: `"never"`, `"always"`, `"timeWindow"`
{{% /md %}}</dd>

    <dt class="property-optional"
            title="Optional">
        <span>scaling_<wbr>down_<wbr>policies</span>
        <span class="property-indicator"></span>
        <span class="property-type"><a href="#elastigroupscalingdownpolicy">List[Elastigroup<wbr>Scaling<wbr>Down<wbr>Policy]</a></span>
    </dt>
    <dd>{{% md %}}{{% /md %}}</dd>

    <dt class="property-optional"
            title="Optional">
        <span>scaling_<wbr>strategies</span>
        <span class="property-indicator"></span>
        <span class="property-type"><a href="#elastigroupscalingstrategy">List[Elastigroup<wbr>Scaling<wbr>Strategy]</a></span>
    </dt>
    <dd>{{% md %}}Set termination policy.
{{% /md %}}</dd>

    <dt class="property-optional"
            title="Optional">
        <span>scaling_<wbr>target_<wbr>policies</span>
        <span class="property-indicator"></span>
        <span class="property-type"><a href="#elastigroupscalingtargetpolicy">List[Elastigroup<wbr>Scaling<wbr>Target<wbr>Policy]</a></span>
    </dt>
    <dd>{{% md %}}{{% /md %}}</dd>

    <dt class="property-optional"
            title="Optional">
        <span>scaling_<wbr>up_<wbr>policies</span>
        <span class="property-indicator"></span>
        <span class="property-type"><a href="#elastigroupscalinguppolicy">List[Elastigroup<wbr>Scaling<wbr>Up<wbr>Policy]</a></span>
    </dt>
    <dd>{{% md %}}{{% /md %}}</dd>

    <dt class="property-optional"
            title="Optional">
        <span>scheduled_<wbr>tasks</span>
        <span class="property-indicator"></span>
        <span class="property-type"><a href="#elastigroupscheduledtask">List[Elastigroup<wbr>Scheduled<wbr>Task]</a></span>
    </dt>
    <dd>{{% md %}}{{% /md %}}</dd>

    <dt class="property-optional"
            title="Optional">
        <span>security_<wbr>groups</span>
        <span class="property-indicator"></span>
        <span class="property-type">List[str]</span>
    </dt>
    <dd>{{% md %}}A list of associated security group IDS.
{{% /md %}}</dd>

    <dt class="property-optional"
            title="Optional">
        <span>shutdown_<wbr>script</span>
        <span class="property-indicator"></span>
        <span class="property-type">str</span>
    </dt>
    <dd>{{% md %}}The Base64-encoded shutdown script that executes prior to instance termination, for more information please see: [Shutdown Script](https://api.spotinst.com/integration-docs/elastigroup/concepts/compute-concepts/shutdown-scripts/)
{{% /md %}}</dd>

    <dt class="property-optional"
            title="Optional">
        <span>signals</span>
        <span class="property-indicator"></span>
        <span class="property-type"><a href="#elastigroupsignal">List[Elastigroup<wbr>Signal]</a></span>
    </dt>
    <dd>{{% md %}}{{% /md %}}</dd>

    <dt class="property-optional"
            title="Optional">
        <span>spot_<wbr>percentage</span>
        <span class="property-indicator"></span>
        <span class="property-type">float</span>
    </dt>
    <dd>{{% md %}}The percentage of Spot instances that would spin up from the `desired_capacity` number.
{{% /md %}}</dd>

    <dt class="property-optional"
            title="Optional">
        <span>stateful_<wbr>deallocation</span>
        <span class="property-indicator"></span>
        <span class="property-type"><a href="#elastigroupstatefuldeallocation">Dict[Elastigroup<wbr>Stateful<wbr>Deallocation]</a></span>
    </dt>
    <dd>{{% md %}}{{% /md %}}</dd>

    <dt class="property-optional"
            title="Optional">
        <span>subnet_<wbr>ids</span>
        <span class="property-indicator"></span>
        <span class="property-type">List[str]</span>
    </dt>
    <dd>{{% md %}}List of Strings of subnet identifiers.
Note: When this parameter is set, `availability_zones` should be left unused.
{{% /md %}}</dd>

    <dt class="property-optional"
            title="Optional">
        <span>tags</span>
        <span class="property-indicator"></span>
        <span class="property-type"><a href="#elastigrouptag">List[Elastigroup<wbr>Tag]</a></span>
    </dt>
    <dd>{{% md %}}A key/value mapping of tags to assign to the resource.
{{% /md %}}</dd>

    <dt class="property-optional"
            title="Optional">
        <span>target_<wbr>group_<wbr>arns</span>
        <span class="property-indicator"></span>
        <span class="property-type">List[str]</span>
    </dt>
    <dd>{{% md %}}{{% /md %}}</dd>

    <dt class="property-optional"
            title="Optional">
        <span>update_<wbr>policy</span>
        <span class="property-indicator"></span>
        <span class="property-type"><a href="#elastigroupupdatepolicy">Dict[Elastigroup<wbr>Update<wbr>Policy]</a></span>
    </dt>
    <dd>{{% md %}}{{% /md %}}</dd>

    <dt class="property-optional"
            title="Optional">
        <span>user_<wbr>data</span>
        <span class="property-indicator"></span>
        <span class="property-type">str</span>
    </dt>
    <dd>{{% md %}}The user data to provide when launching the instance.
{{% /md %}}</dd>

    <dt class="property-optional"
            title="Optional">
        <span>utilize_<wbr>reserved_<wbr>instances</span>
        <span class="property-indicator"></span>
        <span class="property-type">bool</span>
    </dt>
    <dd>{{% md %}}In a case of any available reserved instances, Elastigroup will utilize them first before purchasing Spot instances.
{{% /md %}}</dd>

    <dt class="property-optional"
            title="Optional">
        <span>wait_<wbr>for_<wbr>capacity</span>
        <span class="property-indicator"></span>
        <span class="property-type">float</span>
    </dt>
    <dd>{{% md %}}Minimum number of instances in a 'HEALTHY' status that is required before continuing. This is ignored when updating with blue/green deployment. Cannot exceed `desired_capacity`.
{{% /md %}}</dd>

    <dt class="property-optional"
            title="Optional">
        <span>wait_<wbr>for_<wbr>capacity_<wbr>timeout</span>
        <span class="property-indicator"></span>
        <span class="property-type">float</span>
    </dt>
    <dd>{{% md %}}Time (seconds) to wait for instances to report a 'HEALTHY' status. Useful for plans with multiple dependencies that take some time to initialize. Leave undefined or set to `0` to indicate no wait. This is ignored when updating with blue/green deployment. 
{{% /md %}}</dd>

</dl>
{{% /choosable %}}










## Supporting Types

<h4>Elastigroup<wbr>Ebs<wbr>Block<wbr>Device</h4>
{{% choosable language nodejs %}}
> See the <a href="/docs/reference/pkg/nodejs/pulumi/spotinst/types/input/#ElastigroupEbsBlockDevice">input</a> and <a href="/docs/reference/pkg/nodejs/pulumi/spotinst/types/output/#ElastigroupEbsBlockDevice">output</a> API doc for this type.
{{% /choosable %}}

{{% choosable language go %}}
> See the <a href="https://pkg.go.dev/github.com/pulumi/pulumi-spotinst/sdk/go/spotinst/aws?tab=doc#ElastigroupEbsBlockDeviceArgs">input</a> and <a href="https://pkg.go.dev/github.com/pulumi/pulumi-spotinst/sdk/go/spotinst/aws?tab=doc#ElastigroupEbsBlockDeviceOutput">output</a> API doc for this type.
{{% /choosable %}}




{{% choosable language csharp %}}
<dl class="resources-properties">

    <dt class="property-optional"
            title="Optional">
        <span>Delete<wbr>On<wbr>Termination</span>
        <span class="property-indicator"></span>
        <span class="property-type">bool?</span>
    </dt>
    <dd>{{% md %}}{{% /md %}}</dd>

    <dt class="property-required"
            title="Required">
        <span>Device<wbr>Name</span>
        <span class="property-indicator"></span>
        <span class="property-type">string</span>
    </dt>
    <dd>{{% md %}}{{% /md %}}</dd>

    <dt class="property-optional"
            title="Optional">
        <span>Encrypted</span>
        <span class="property-indicator"></span>
        <span class="property-type">bool?</span>
    </dt>
    <dd>{{% md %}}{{% /md %}}</dd>

    <dt class="property-optional"
            title="Optional">
        <span>Iops</span>
        <span class="property-indicator"></span>
        <span class="property-type">int?</span>
    </dt>
    <dd>{{% md %}}{{% /md %}}</dd>

    <dt class="property-optional"
            title="Optional">
        <span>Kms<wbr>Key<wbr>Id</span>
        <span class="property-indicator"></span>
        <span class="property-type">string?</span>
    </dt>
    <dd>{{% md %}}{{% /md %}}</dd>

    <dt class="property-optional"
            title="Optional">
        <span>Snapshot<wbr>Id</span>
        <span class="property-indicator"></span>
        <span class="property-type">string?</span>
    </dt>
    <dd>{{% md %}}{{% /md %}}</dd>

    <dt class="property-optional"
            title="Optional">
        <span>Volume<wbr>Size</span>
        <span class="property-indicator"></span>
        <span class="property-type">int?</span>
    </dt>
    <dd>{{% md %}}{{% /md %}}</dd>

    <dt class="property-optional"
            title="Optional">
        <span>Volume<wbr>Type</span>
        <span class="property-indicator"></span>
        <span class="property-type">string?</span>
    </dt>
    <dd>{{% md %}}{{% /md %}}</dd>

</dl>
{{% /choosable %}}


{{% choosable language go %}}
<dl class="resources-properties">

    <dt class="property-optional"
            title="Optional">
        <span>Delete<wbr>On<wbr>Termination</span>
        <span class="property-indicator"></span>
        <span class="property-type">*bool</span>
    </dt>
    <dd>{{% md %}}{{% /md %}}</dd>

    <dt class="property-required"
            title="Required">
        <span>Device<wbr>Name</span>
        <span class="property-indicator"></span>
        <span class="property-type">string</span>
    </dt>
    <dd>{{% md %}}{{% /md %}}</dd>

    <dt class="property-optional"
            title="Optional">
        <span>Encrypted</span>
        <span class="property-indicator"></span>
        <span class="property-type">*bool</span>
    </dt>
    <dd>{{% md %}}{{% /md %}}</dd>

    <dt class="property-optional"
            title="Optional">
        <span>Iops</span>
        <span class="property-indicator"></span>
        <span class="property-type">*int</span>
    </dt>
    <dd>{{% md %}}{{% /md %}}</dd>

    <dt class="property-optional"
            title="Optional">
        <span>Kms<wbr>Key<wbr>Id</span>
        <span class="property-indicator"></span>
        <span class="property-type">*string</span>
    </dt>
    <dd>{{% md %}}{{% /md %}}</dd>

    <dt class="property-optional"
            title="Optional">
        <span>Snapshot<wbr>Id</span>
        <span class="property-indicator"></span>
        <span class="property-type">*string</span>
    </dt>
    <dd>{{% md %}}{{% /md %}}</dd>

    <dt class="property-optional"
            title="Optional">
        <span>Volume<wbr>Size</span>
        <span class="property-indicator"></span>
        <span class="property-type">*int</span>
    </dt>
    <dd>{{% md %}}{{% /md %}}</dd>

    <dt class="property-optional"
            title="Optional">
        <span>Volume<wbr>Type</span>
        <span class="property-indicator"></span>
        <span class="property-type">*string</span>
    </dt>
    <dd>{{% md %}}{{% /md %}}</dd>

</dl>
{{% /choosable %}}


{{% choosable language nodejs %}}
<dl class="resources-properties">

    <dt class="property-optional"
            title="Optional">
        <span>delete<wbr>On<wbr>Termination</span>
        <span class="property-indicator"></span>
        <span class="property-type">boolean?</span>
    </dt>
    <dd>{{% md %}}{{% /md %}}</dd>

    <dt class="property-required"
            title="Required">
        <span>device<wbr>Name</span>
        <span class="property-indicator"></span>
        <span class="property-type">string</span>
    </dt>
    <dd>{{% md %}}{{% /md %}}</dd>

    <dt class="property-optional"
            title="Optional">
        <span>encrypted</span>
        <span class="property-indicator"></span>
        <span class="property-type">boolean?</span>
    </dt>
    <dd>{{% md %}}{{% /md %}}</dd>

    <dt class="property-optional"
            title="Optional">
        <span>iops</span>
        <span class="property-indicator"></span>
        <span class="property-type">number?</span>
    </dt>
    <dd>{{% md %}}{{% /md %}}</dd>

    <dt class="property-optional"
            title="Optional">
        <span>kms<wbr>Key<wbr>Id</span>
        <span class="property-indicator"></span>
        <span class="property-type">string?</span>
    </dt>
    <dd>{{% md %}}{{% /md %}}</dd>

    <dt class="property-optional"
            title="Optional">
        <span>snapshot<wbr>Id</span>
        <span class="property-indicator"></span>
        <span class="property-type">string?</span>
    </dt>
    <dd>{{% md %}}{{% /md %}}</dd>

    <dt class="property-optional"
            title="Optional">
        <span>volume<wbr>Size</span>
        <span class="property-indicator"></span>
        <span class="property-type">number?</span>
    </dt>
    <dd>{{% md %}}{{% /md %}}</dd>

    <dt class="property-optional"
            title="Optional">
        <span>volume<wbr>Type</span>
        <span class="property-indicator"></span>
        <span class="property-type">string?</span>
    </dt>
    <dd>{{% md %}}{{% /md %}}</dd>

</dl>
{{% /choosable %}}


{{% choosable language python %}}
<dl class="resources-properties">

    <dt class="property-optional"
            title="Optional">
        <span>delete<wbr>On<wbr>Termination</span>
        <span class="property-indicator"></span>
        <span class="property-type">bool</span>
    </dt>
    <dd>{{% md %}}{{% /md %}}</dd>

    <dt class="property-required"
            title="Required">
        <span>device<wbr>Name</span>
        <span class="property-indicator"></span>
        <span class="property-type">str</span>
    </dt>
    <dd>{{% md %}}{{% /md %}}</dd>

    <dt class="property-optional"
            title="Optional">
        <span>encrypted</span>
        <span class="property-indicator"></span>
        <span class="property-type">bool</span>
    </dt>
    <dd>{{% md %}}{{% /md %}}</dd>

    <dt class="property-optional"
            title="Optional">
        <span>iops</span>
        <span class="property-indicator"></span>
        <span class="property-type">float</span>
    </dt>
    <dd>{{% md %}}{{% /md %}}</dd>

    <dt class="property-optional"
            title="Optional">
        <span>kms<wbr>Key<wbr>Id</span>
        <span class="property-indicator"></span>
        <span class="property-type">str</span>
    </dt>
    <dd>{{% md %}}{{% /md %}}</dd>

    <dt class="property-optional"
            title="Optional">
        <span>snapshot<wbr>Id</span>
        <span class="property-indicator"></span>
        <span class="property-type">str</span>
    </dt>
    <dd>{{% md %}}{{% /md %}}</dd>

    <dt class="property-optional"
            title="Optional">
        <span>volume<wbr>Size</span>
        <span class="property-indicator"></span>
        <span class="property-type">float</span>
    </dt>
    <dd>{{% md %}}{{% /md %}}</dd>

    <dt class="property-optional"
            title="Optional">
        <span>volume<wbr>Type</span>
        <span class="property-indicator"></span>
        <span class="property-type">str</span>
    </dt>
    <dd>{{% md %}}{{% /md %}}</dd>

</dl>
{{% /choosable %}}





<h4>Elastigroup<wbr>Ephemeral<wbr>Block<wbr>Device</h4>
{{% choosable language nodejs %}}
> See the <a href="/docs/reference/pkg/nodejs/pulumi/spotinst/types/input/#ElastigroupEphemeralBlockDevice">input</a> and <a href="/docs/reference/pkg/nodejs/pulumi/spotinst/types/output/#ElastigroupEphemeralBlockDevice">output</a> API doc for this type.
{{% /choosable %}}

{{% choosable language go %}}
> See the <a href="https://pkg.go.dev/github.com/pulumi/pulumi-spotinst/sdk/go/spotinst/aws?tab=doc#ElastigroupEphemeralBlockDeviceArgs">input</a> and <a href="https://pkg.go.dev/github.com/pulumi/pulumi-spotinst/sdk/go/spotinst/aws?tab=doc#ElastigroupEphemeralBlockDeviceOutput">output</a> API doc for this type.
{{% /choosable %}}




{{% choosable language csharp %}}
<dl class="resources-properties">

    <dt class="property-required"
            title="Required">
        <span>Device<wbr>Name</span>
        <span class="property-indicator"></span>
        <span class="property-type">string</span>
    </dt>
    <dd>{{% md %}}{{% /md %}}</dd>

    <dt class="property-required"
            title="Required">
        <span>Virtual<wbr>Name</span>
        <span class="property-indicator"></span>
        <span class="property-type">string</span>
    </dt>
    <dd>{{% md %}}{{% /md %}}</dd>

</dl>
{{% /choosable %}}


{{% choosable language go %}}
<dl class="resources-properties">

    <dt class="property-required"
            title="Required">
        <span>Device<wbr>Name</span>
        <span class="property-indicator"></span>
        <span class="property-type">string</span>
    </dt>
    <dd>{{% md %}}{{% /md %}}</dd>

    <dt class="property-required"
            title="Required">
        <span>Virtual<wbr>Name</span>
        <span class="property-indicator"></span>
        <span class="property-type">string</span>
    </dt>
    <dd>{{% md %}}{{% /md %}}</dd>

</dl>
{{% /choosable %}}


{{% choosable language nodejs %}}
<dl class="resources-properties">

    <dt class="property-required"
            title="Required">
        <span>device<wbr>Name</span>
        <span class="property-indicator"></span>
        <span class="property-type">string</span>
    </dt>
    <dd>{{% md %}}{{% /md %}}</dd>

    <dt class="property-required"
            title="Required">
        <span>virtual<wbr>Name</span>
        <span class="property-indicator"></span>
        <span class="property-type">string</span>
    </dt>
    <dd>{{% md %}}{{% /md %}}</dd>

</dl>
{{% /choosable %}}


{{% choosable language python %}}
<dl class="resources-properties">

    <dt class="property-required"
            title="Required">
        <span>device<wbr>Name</span>
        <span class="property-indicator"></span>
        <span class="property-type">str</span>
    </dt>
    <dd>{{% md %}}{{% /md %}}</dd>

    <dt class="property-required"
            title="Required">
        <span>virtual<wbr>Name</span>
        <span class="property-indicator"></span>
        <span class="property-type">str</span>
    </dt>
    <dd>{{% md %}}{{% /md %}}</dd>

</dl>
{{% /choosable %}}





<h4>Elastigroup<wbr>Instance<wbr>Types<wbr>Weight</h4>
{{% choosable language nodejs %}}
> See the <a href="/docs/reference/pkg/nodejs/pulumi/spotinst/types/input/#ElastigroupInstanceTypesWeight">input</a> and <a href="/docs/reference/pkg/nodejs/pulumi/spotinst/types/output/#ElastigroupInstanceTypesWeight">output</a> API doc for this type.
{{% /choosable %}}

{{% choosable language go %}}
> See the <a href="https://pkg.go.dev/github.com/pulumi/pulumi-spotinst/sdk/go/spotinst/aws?tab=doc#ElastigroupInstanceTypesWeightArgs">input</a> and <a href="https://pkg.go.dev/github.com/pulumi/pulumi-spotinst/sdk/go/spotinst/aws?tab=doc#ElastigroupInstanceTypesWeightOutput">output</a> API doc for this type.
{{% /choosable %}}




{{% choosable language csharp %}}
<dl class="resources-properties">

    <dt class="property-required"
            title="Required">
        <span>Instance<wbr>Type</span>
        <span class="property-indicator"></span>
        <span class="property-type">string</span>
    </dt>
    <dd>{{% md %}}Name of instance type (String).
{{% /md %}}</dd>

    <dt class="property-required"
            title="Required">
        <span>Weight</span>
        <span class="property-indicator"></span>
        <span class="property-type">int</span>
    </dt>
    <dd>{{% md %}}Weight per instance type (Integer).
{{% /md %}}</dd>

</dl>
{{% /choosable %}}


{{% choosable language go %}}
<dl class="resources-properties">

    <dt class="property-required"
            title="Required">
        <span>Instance<wbr>Type</span>
        <span class="property-indicator"></span>
        <span class="property-type">string</span>
    </dt>
    <dd>{{% md %}}Name of instance type (String).
{{% /md %}}</dd>

    <dt class="property-required"
            title="Required">
        <span>Weight</span>
        <span class="property-indicator"></span>
        <span class="property-type">int</span>
    </dt>
    <dd>{{% md %}}Weight per instance type (Integer).
{{% /md %}}</dd>

</dl>
{{% /choosable %}}


{{% choosable language nodejs %}}
<dl class="resources-properties">

    <dt class="property-required"
            title="Required">
        <span>instance<wbr>Type</span>
        <span class="property-indicator"></span>
        <span class="property-type">string</span>
    </dt>
    <dd>{{% md %}}Name of instance type (String).
{{% /md %}}</dd>

    <dt class="property-required"
            title="Required">
        <span>weight</span>
        <span class="property-indicator"></span>
        <span class="property-type">number</span>
    </dt>
    <dd>{{% md %}}Weight per instance type (Integer).
{{% /md %}}</dd>

</dl>
{{% /choosable %}}


{{% choosable language python %}}
<dl class="resources-properties">

    <dt class="property-required"
            title="Required">
        <span>instance<wbr>Type</span>
        <span class="property-indicator"></span>
        <span class="property-type">str</span>
    </dt>
    <dd>{{% md %}}Name of instance type (String).
{{% /md %}}</dd>

    <dt class="property-required"
            title="Required">
        <span>weight</span>
        <span class="property-indicator"></span>
        <span class="property-type">float</span>
    </dt>
    <dd>{{% md %}}Weight per instance type (Integer).
{{% /md %}}</dd>

</dl>
{{% /choosable %}}





<h4>Elastigroup<wbr>Integration<wbr>Beanstalk</h4>
{{% choosable language nodejs %}}
> See the <a href="/docs/reference/pkg/nodejs/pulumi/spotinst/types/input/#ElastigroupIntegrationBeanstalk">input</a> and <a href="/docs/reference/pkg/nodejs/pulumi/spotinst/types/output/#ElastigroupIntegrationBeanstalk">output</a> API doc for this type.
{{% /choosable %}}

{{% choosable language go %}}
> See the <a href="https://pkg.go.dev/github.com/pulumi/pulumi-spotinst/sdk/go/spotinst/aws?tab=doc#ElastigroupIntegrationBeanstalkArgs">input</a> and <a href="https://pkg.go.dev/github.com/pulumi/pulumi-spotinst/sdk/go/spotinst/aws?tab=doc#ElastigroupIntegrationBeanstalkOutput">output</a> API doc for this type.
{{% /choosable %}}




{{% choosable language csharp %}}
<dl class="resources-properties">

    <dt class="property-optional"
            title="Optional">
        <span>Deployment<wbr>Preferences</span>
        <span class="property-indicator"></span>
        <span class="property-type"><a href="#elastigroupintegrationbeanstalkdeploymentpreferences">Elastigroup<wbr>Integration<wbr>Beanstalk<wbr>Deployment<wbr>Preferences<wbr>Args?</a></span>
    </dt>
    <dd>{{% md %}}{{% /md %}}</dd>

    <dt class="property-optional"
            title="Optional">
        <span>Environment<wbr>Id</span>
        <span class="property-indicator"></span>
        <span class="property-type">string?</span>
    </dt>
    <dd>{{% md %}}{{% /md %}}</dd>

    <dt class="property-optional"
            title="Optional">
        <span>Managed<wbr>Actions</span>
        <span class="property-indicator"></span>
        <span class="property-type"><a href="#elastigroupintegrationbeanstalkmanagedactions">Elastigroup<wbr>Integration<wbr>Beanstalk<wbr>Managed<wbr>Actions<wbr>Args?</a></span>
    </dt>
    <dd>{{% md %}}{{% /md %}}</dd>

</dl>
{{% /choosable %}}


{{% choosable language go %}}
<dl class="resources-properties">

    <dt class="property-optional"
            title="Optional">
        <span>Deployment<wbr>Preferences</span>
        <span class="property-indicator"></span>
        <span class="property-type"><a href="#elastigroupintegrationbeanstalkdeploymentpreferences">*Elastigroup<wbr>Integration<wbr>Beanstalk<wbr>Deployment<wbr>Preferences</a></span>
    </dt>
    <dd>{{% md %}}{{% /md %}}</dd>

    <dt class="property-optional"
            title="Optional">
        <span>Environment<wbr>Id</span>
        <span class="property-indicator"></span>
        <span class="property-type">*string</span>
    </dt>
    <dd>{{% md %}}{{% /md %}}</dd>

    <dt class="property-optional"
            title="Optional">
        <span>Managed<wbr>Actions</span>
        <span class="property-indicator"></span>
        <span class="property-type"><a href="#elastigroupintegrationbeanstalkmanagedactions">*Elastigroup<wbr>Integration<wbr>Beanstalk<wbr>Managed<wbr>Actions</a></span>
    </dt>
    <dd>{{% md %}}{{% /md %}}</dd>

</dl>
{{% /choosable %}}


{{% choosable language nodejs %}}
<dl class="resources-properties">

    <dt class="property-optional"
            title="Optional">
        <span>deployment<wbr>Preferences</span>
        <span class="property-indicator"></span>
        <span class="property-type"><a href="#elastigroupintegrationbeanstalkdeploymentpreferences">Elastigroup<wbr>Integration<wbr>Beanstalk<wbr>Deployment<wbr>Preferences?</a></span>
    </dt>
    <dd>{{% md %}}{{% /md %}}</dd>

    <dt class="property-optional"
            title="Optional">
        <span>environment<wbr>Id</span>
        <span class="property-indicator"></span>
        <span class="property-type">string?</span>
    </dt>
    <dd>{{% md %}}{{% /md %}}</dd>

    <dt class="property-optional"
            title="Optional">
        <span>managed<wbr>Actions</span>
        <span class="property-indicator"></span>
        <span class="property-type"><a href="#elastigroupintegrationbeanstalkmanagedactions">Elastigroup<wbr>Integration<wbr>Beanstalk<wbr>Managed<wbr>Actions?</a></span>
    </dt>
    <dd>{{% md %}}{{% /md %}}</dd>

</dl>
{{% /choosable %}}


{{% choosable language python %}}
<dl class="resources-properties">

    <dt class="property-optional"
            title="Optional">
        <span>deployment_<wbr>preferences</span>
        <span class="property-indicator"></span>
        <span class="property-type"><a href="#elastigroupintegrationbeanstalkdeploymentpreferences">Dict[Elastigroup<wbr>Integration<wbr>Beanstalk<wbr>Deployment<wbr>Preferences]</a></span>
    </dt>
    <dd>{{% md %}}{{% /md %}}</dd>

    <dt class="property-optional"
            title="Optional">
        <span>environment<wbr>Id</span>
        <span class="property-indicator"></span>
        <span class="property-type">str</span>
    </dt>
    <dd>{{% md %}}{{% /md %}}</dd>

    <dt class="property-optional"
            title="Optional">
        <span>managed_<wbr>actions</span>
        <span class="property-indicator"></span>
        <span class="property-type"><a href="#elastigroupintegrationbeanstalkmanagedactions">Dict[Elastigroup<wbr>Integration<wbr>Beanstalk<wbr>Managed<wbr>Actions]</a></span>
    </dt>
    <dd>{{% md %}}{{% /md %}}</dd>

</dl>
{{% /choosable %}}





<h4>Elastigroup<wbr>Integration<wbr>Beanstalk<wbr>Deployment<wbr>Preferences</h4>
{{% choosable language nodejs %}}
> See the <a href="/docs/reference/pkg/nodejs/pulumi/spotinst/types/input/#ElastigroupIntegrationBeanstalkDeploymentPreferences">input</a> and <a href="/docs/reference/pkg/nodejs/pulumi/spotinst/types/output/#ElastigroupIntegrationBeanstalkDeploymentPreferences">output</a> API doc for this type.
{{% /choosable %}}

{{% choosable language go %}}
> See the <a href="https://pkg.go.dev/github.com/pulumi/pulumi-spotinst/sdk/go/spotinst/aws?tab=doc#ElastigroupIntegrationBeanstalkDeploymentPreferencesArgs">input</a> and <a href="https://pkg.go.dev/github.com/pulumi/pulumi-spotinst/sdk/go/spotinst/aws?tab=doc#ElastigroupIntegrationBeanstalkDeploymentPreferencesOutput">output</a> API doc for this type.
{{% /choosable %}}




{{% choosable language csharp %}}
<dl class="resources-properties">

    <dt class="property-optional"
            title="Optional">
        <span>Automatic<wbr>Roll</span>
        <span class="property-indicator"></span>
        <span class="property-type">bool?</span>
    </dt>
    <dd>{{% md %}}{{% /md %}}</dd>

    <dt class="property-optional"
            title="Optional">
        <span>Batch<wbr>Size<wbr>Percentage</span>
        <span class="property-indicator"></span>
        <span class="property-type">int?</span>
    </dt>
    <dd>{{% md %}}{{% /md %}}</dd>

    <dt class="property-optional"
            title="Optional">
        <span>Grace<wbr>Period</span>
        <span class="property-indicator"></span>
        <span class="property-type">int?</span>
    </dt>
    <dd>{{% md %}}{{% /md %}}</dd>

    <dt class="property-optional"
            title="Optional">
        <span>Strategy</span>
        <span class="property-indicator"></span>
        <span class="property-type"><a href="#elastigroupintegrationbeanstalkdeploymentpreferencesstrategy">Elastigroup<wbr>Integration<wbr>Beanstalk<wbr>Deployment<wbr>Preferences<wbr>Strategy<wbr>Args?</a></span>
    </dt>
    <dd>{{% md %}}{{% /md %}}</dd>

</dl>
{{% /choosable %}}


{{% choosable language go %}}
<dl class="resources-properties">

    <dt class="property-optional"
            title="Optional">
        <span>Automatic<wbr>Roll</span>
        <span class="property-indicator"></span>
        <span class="property-type">*bool</span>
    </dt>
    <dd>{{% md %}}{{% /md %}}</dd>

    <dt class="property-optional"
            title="Optional">
        <span>Batch<wbr>Size<wbr>Percentage</span>
        <span class="property-indicator"></span>
        <span class="property-type">*int</span>
    </dt>
    <dd>{{% md %}}{{% /md %}}</dd>

    <dt class="property-optional"
            title="Optional">
        <span>Grace<wbr>Period</span>
        <span class="property-indicator"></span>
        <span class="property-type">*int</span>
    </dt>
    <dd>{{% md %}}{{% /md %}}</dd>

    <dt class="property-optional"
            title="Optional">
        <span>Strategy</span>
        <span class="property-indicator"></span>
        <span class="property-type"><a href="#elastigroupintegrationbeanstalkdeploymentpreferencesstrategy">*Elastigroup<wbr>Integration<wbr>Beanstalk<wbr>Deployment<wbr>Preferences<wbr>Strategy</a></span>
    </dt>
    <dd>{{% md %}}{{% /md %}}</dd>

</dl>
{{% /choosable %}}


{{% choosable language nodejs %}}
<dl class="resources-properties">

    <dt class="property-optional"
            title="Optional">
        <span>automatic<wbr>Roll</span>
        <span class="property-indicator"></span>
        <span class="property-type">boolean?</span>
    </dt>
    <dd>{{% md %}}{{% /md %}}</dd>

    <dt class="property-optional"
            title="Optional">
        <span>batch<wbr>Size<wbr>Percentage</span>
        <span class="property-indicator"></span>
        <span class="property-type">number?</span>
    </dt>
    <dd>{{% md %}}{{% /md %}}</dd>

    <dt class="property-optional"
            title="Optional">
        <span>grace<wbr>Period</span>
        <span class="property-indicator"></span>
        <span class="property-type">number?</span>
    </dt>
    <dd>{{% md %}}{{% /md %}}</dd>

    <dt class="property-optional"
            title="Optional">
        <span>strategy</span>
        <span class="property-indicator"></span>
        <span class="property-type"><a href="#elastigroupintegrationbeanstalkdeploymentpreferencesstrategy">Elastigroup<wbr>Integration<wbr>Beanstalk<wbr>Deployment<wbr>Preferences<wbr>Strategy?</a></span>
    </dt>
    <dd>{{% md %}}{{% /md %}}</dd>

</dl>
{{% /choosable %}}


{{% choosable language python %}}
<dl class="resources-properties">

    <dt class="property-optional"
            title="Optional">
        <span>automatic<wbr>Roll</span>
        <span class="property-indicator"></span>
        <span class="property-type">bool</span>
    </dt>
    <dd>{{% md %}}{{% /md %}}</dd>

    <dt class="property-optional"
            title="Optional">
        <span>batch<wbr>Size<wbr>Percentage</span>
        <span class="property-indicator"></span>
        <span class="property-type">float</span>
    </dt>
    <dd>{{% md %}}{{% /md %}}</dd>

    <dt class="property-optional"
            title="Optional">
        <span>grace_<wbr>period</span>
        <span class="property-indicator"></span>
        <span class="property-type">float</span>
    </dt>
    <dd>{{% md %}}{{% /md %}}</dd>

    <dt class="property-optional"
            title="Optional">
        <span>strategy</span>
        <span class="property-indicator"></span>
        <span class="property-type"><a href="#elastigroupintegrationbeanstalkdeploymentpreferencesstrategy">Dict[Elastigroup<wbr>Integration<wbr>Beanstalk<wbr>Deployment<wbr>Preferences<wbr>Strategy]</a></span>
    </dt>
    <dd>{{% md %}}{{% /md %}}</dd>

</dl>
{{% /choosable %}}





<h4>Elastigroup<wbr>Integration<wbr>Beanstalk<wbr>Deployment<wbr>Preferences<wbr>Strategy</h4>
{{% choosable language nodejs %}}
> See the <a href="/docs/reference/pkg/nodejs/pulumi/spotinst/types/input/#ElastigroupIntegrationBeanstalkDeploymentPreferencesStrategy">input</a> and <a href="/docs/reference/pkg/nodejs/pulumi/spotinst/types/output/#ElastigroupIntegrationBeanstalkDeploymentPreferencesStrategy">output</a> API doc for this type.
{{% /choosable %}}

{{% choosable language go %}}
> See the <a href="https://pkg.go.dev/github.com/pulumi/pulumi-spotinst/sdk/go/spotinst/aws?tab=doc#ElastigroupIntegrationBeanstalkDeploymentPreferencesStrategyArgs">input</a> and <a href="https://pkg.go.dev/github.com/pulumi/pulumi-spotinst/sdk/go/spotinst/aws?tab=doc#ElastigroupIntegrationBeanstalkDeploymentPreferencesStrategyOutput">output</a> API doc for this type.
{{% /choosable %}}




{{% choosable language csharp %}}
<dl class="resources-properties">

    <dt class="property-optional"
            title="Optional">
        <span>Action</span>
        <span class="property-indicator"></span>
        <span class="property-type">string?</span>
    </dt>
    <dd>{{% md %}}{{% /md %}}</dd>

    <dt class="property-optional"
            title="Optional">
        <span>Should<wbr>Drain<wbr>Instances</span>
        <span class="property-indicator"></span>
        <span class="property-type">bool?</span>
    </dt>
    <dd>{{% md %}}{{% /md %}}</dd>

</dl>
{{% /choosable %}}


{{% choosable language go %}}
<dl class="resources-properties">

    <dt class="property-optional"
            title="Optional">
        <span>Action</span>
        <span class="property-indicator"></span>
        <span class="property-type">*string</span>
    </dt>
    <dd>{{% md %}}{{% /md %}}</dd>

    <dt class="property-optional"
            title="Optional">
        <span>Should<wbr>Drain<wbr>Instances</span>
        <span class="property-indicator"></span>
        <span class="property-type">*bool</span>
    </dt>
    <dd>{{% md %}}{{% /md %}}</dd>

</dl>
{{% /choosable %}}


{{% choosable language nodejs %}}
<dl class="resources-properties">

    <dt class="property-optional"
            title="Optional">
        <span>action</span>
        <span class="property-indicator"></span>
        <span class="property-type">string?</span>
    </dt>
    <dd>{{% md %}}{{% /md %}}</dd>

    <dt class="property-optional"
            title="Optional">
        <span>should<wbr>Drain<wbr>Instances</span>
        <span class="property-indicator"></span>
        <span class="property-type">boolean?</span>
    </dt>
    <dd>{{% md %}}{{% /md %}}</dd>

</dl>
{{% /choosable %}}


{{% choosable language python %}}
<dl class="resources-properties">

    <dt class="property-optional"
            title="Optional">
        <span>action</span>
        <span class="property-indicator"></span>
        <span class="property-type">str</span>
    </dt>
    <dd>{{% md %}}{{% /md %}}</dd>

    <dt class="property-optional"
            title="Optional">
        <span>should<wbr>Drain<wbr>Instances</span>
        <span class="property-indicator"></span>
        <span class="property-type">bool</span>
    </dt>
    <dd>{{% md %}}{{% /md %}}</dd>

</dl>
{{% /choosable %}}





<h4>Elastigroup<wbr>Integration<wbr>Beanstalk<wbr>Managed<wbr>Actions</h4>
{{% choosable language nodejs %}}
> See the <a href="/docs/reference/pkg/nodejs/pulumi/spotinst/types/input/#ElastigroupIntegrationBeanstalkManagedActions">input</a> and <a href="/docs/reference/pkg/nodejs/pulumi/spotinst/types/output/#ElastigroupIntegrationBeanstalkManagedActions">output</a> API doc for this type.
{{% /choosable %}}

{{% choosable language go %}}
> See the <a href="https://pkg.go.dev/github.com/pulumi/pulumi-spotinst/sdk/go/spotinst/aws?tab=doc#ElastigroupIntegrationBeanstalkManagedActionsArgs">input</a> and <a href="https://pkg.go.dev/github.com/pulumi/pulumi-spotinst/sdk/go/spotinst/aws?tab=doc#ElastigroupIntegrationBeanstalkManagedActionsOutput">output</a> API doc for this type.
{{% /choosable %}}




{{% choosable language csharp %}}
<dl class="resources-properties">

    <dt class="property-optional"
            title="Optional">
        <span>Platform<wbr>Update</span>
        <span class="property-indicator"></span>
        <span class="property-type"><a href="#elastigroupintegrationbeanstalkmanagedactionsplatformupdate">Elastigroup<wbr>Integration<wbr>Beanstalk<wbr>Managed<wbr>Actions<wbr>Platform<wbr>Update<wbr>Args?</a></span>
    </dt>
    <dd>{{% md %}}{{% /md %}}</dd>

</dl>
{{% /choosable %}}


{{% choosable language go %}}
<dl class="resources-properties">

    <dt class="property-optional"
            title="Optional">
        <span>Platform<wbr>Update</span>
        <span class="property-indicator"></span>
        <span class="property-type"><a href="#elastigroupintegrationbeanstalkmanagedactionsplatformupdate">*Elastigroup<wbr>Integration<wbr>Beanstalk<wbr>Managed<wbr>Actions<wbr>Platform<wbr>Update</a></span>
    </dt>
    <dd>{{% md %}}{{% /md %}}</dd>

</dl>
{{% /choosable %}}


{{% choosable language nodejs %}}
<dl class="resources-properties">

    <dt class="property-optional"
            title="Optional">
        <span>platform<wbr>Update</span>
        <span class="property-indicator"></span>
        <span class="property-type"><a href="#elastigroupintegrationbeanstalkmanagedactionsplatformupdate">Elastigroup<wbr>Integration<wbr>Beanstalk<wbr>Managed<wbr>Actions<wbr>Platform<wbr>Update?</a></span>
    </dt>
    <dd>{{% md %}}{{% /md %}}</dd>

</dl>
{{% /choosable %}}


{{% choosable language python %}}
<dl class="resources-properties">

    <dt class="property-optional"
            title="Optional">
        <span>platform<wbr>Update</span>
        <span class="property-indicator"></span>
        <span class="property-type"><a href="#elastigroupintegrationbeanstalkmanagedactionsplatformupdate">Dict[Elastigroup<wbr>Integration<wbr>Beanstalk<wbr>Managed<wbr>Actions<wbr>Platform<wbr>Update]</a></span>
    </dt>
    <dd>{{% md %}}{{% /md %}}</dd>

</dl>
{{% /choosable %}}





<h4>Elastigroup<wbr>Integration<wbr>Beanstalk<wbr>Managed<wbr>Actions<wbr>Platform<wbr>Update</h4>
{{% choosable language nodejs %}}
> See the <a href="/docs/reference/pkg/nodejs/pulumi/spotinst/types/input/#ElastigroupIntegrationBeanstalkManagedActionsPlatformUpdate">input</a> and <a href="/docs/reference/pkg/nodejs/pulumi/spotinst/types/output/#ElastigroupIntegrationBeanstalkManagedActionsPlatformUpdate">output</a> API doc for this type.
{{% /choosable %}}

{{% choosable language go %}}
> See the <a href="https://pkg.go.dev/github.com/pulumi/pulumi-spotinst/sdk/go/spotinst/aws?tab=doc#ElastigroupIntegrationBeanstalkManagedActionsPlatformUpdateArgs">input</a> and <a href="https://pkg.go.dev/github.com/pulumi/pulumi-spotinst/sdk/go/spotinst/aws?tab=doc#ElastigroupIntegrationBeanstalkManagedActionsPlatformUpdateOutput">output</a> API doc for this type.
{{% /choosable %}}




{{% choosable language csharp %}}
<dl class="resources-properties">

    <dt class="property-optional"
            title="Optional">
        <span>Perform<wbr>At</span>
        <span class="property-indicator"></span>
        <span class="property-type">string?</span>
    </dt>
    <dd>{{% md %}}In the event of a fallback to On-Demand instances, select the time period to revert back to Spot. Supported Arguments – always (default), timeWindow, never. For timeWindow or never to be valid the group must have availabilityOriented OR persistence defined.
{{% /md %}}</dd>

    <dt class="property-optional"
            title="Optional">
        <span>Time<wbr>Window</span>
        <span class="property-indicator"></span>
        <span class="property-type">string?</span>
    </dt>
    <dd>{{% md %}}{{% /md %}}</dd>

    <dt class="property-optional"
            title="Optional">
        <span>Update<wbr>Level</span>
        <span class="property-indicator"></span>
        <span class="property-type">string?</span>
    </dt>
    <dd>{{% md %}}{{% /md %}}</dd>

</dl>
{{% /choosable %}}


{{% choosable language go %}}
<dl class="resources-properties">

    <dt class="property-optional"
            title="Optional">
        <span>Perform<wbr>At</span>
        <span class="property-indicator"></span>
        <span class="property-type">*string</span>
    </dt>
    <dd>{{% md %}}In the event of a fallback to On-Demand instances, select the time period to revert back to Spot. Supported Arguments – always (default), timeWindow, never. For timeWindow or never to be valid the group must have availabilityOriented OR persistence defined.
{{% /md %}}</dd>

    <dt class="property-optional"
            title="Optional">
        <span>Time<wbr>Window</span>
        <span class="property-indicator"></span>
        <span class="property-type">*string</span>
    </dt>
    <dd>{{% md %}}{{% /md %}}</dd>

    <dt class="property-optional"
            title="Optional">
        <span>Update<wbr>Level</span>
        <span class="property-indicator"></span>
        <span class="property-type">*string</span>
    </dt>
    <dd>{{% md %}}{{% /md %}}</dd>

</dl>
{{% /choosable %}}


{{% choosable language nodejs %}}
<dl class="resources-properties">

    <dt class="property-optional"
            title="Optional">
        <span>perform<wbr>At</span>
        <span class="property-indicator"></span>
        <span class="property-type">string?</span>
    </dt>
    <dd>{{% md %}}In the event of a fallback to On-Demand instances, select the time period to revert back to Spot. Supported Arguments – always (default), timeWindow, never. For timeWindow or never to be valid the group must have availabilityOriented OR persistence defined.
{{% /md %}}</dd>

    <dt class="property-optional"
            title="Optional">
        <span>time<wbr>Window</span>
        <span class="property-indicator"></span>
        <span class="property-type">string?</span>
    </dt>
    <dd>{{% md %}}{{% /md %}}</dd>

    <dt class="property-optional"
            title="Optional">
        <span>update<wbr>Level</span>
        <span class="property-indicator"></span>
        <span class="property-type">string?</span>
    </dt>
    <dd>{{% md %}}{{% /md %}}</dd>

</dl>
{{% /choosable %}}


{{% choosable language python %}}
<dl class="resources-properties">

    <dt class="property-optional"
            title="Optional">
        <span>perform<wbr>At</span>
        <span class="property-indicator"></span>
        <span class="property-type">str</span>
    </dt>
    <dd>{{% md %}}In the event of a fallback to On-Demand instances, select the time period to revert back to Spot. Supported Arguments – always (default), timeWindow, never. For timeWindow or never to be valid the group must have availabilityOriented OR persistence defined.
{{% /md %}}</dd>

    <dt class="property-optional"
            title="Optional">
        <span>time<wbr>Window</span>
        <span class="property-indicator"></span>
        <span class="property-type">str</span>
    </dt>
    <dd>{{% md %}}{{% /md %}}</dd>

    <dt class="property-optional"
            title="Optional">
        <span>update<wbr>Level</span>
        <span class="property-indicator"></span>
        <span class="property-type">str</span>
    </dt>
    <dd>{{% md %}}{{% /md %}}</dd>

</dl>
{{% /choosable %}}





<h4>Elastigroup<wbr>Integration<wbr>Codedeploy</h4>
{{% choosable language nodejs %}}
> See the <a href="/docs/reference/pkg/nodejs/pulumi/spotinst/types/input/#ElastigroupIntegrationCodedeploy">input</a> and <a href="/docs/reference/pkg/nodejs/pulumi/spotinst/types/output/#ElastigroupIntegrationCodedeploy">output</a> API doc for this type.
{{% /choosable %}}

{{% choosable language go %}}
> See the <a href="https://pkg.go.dev/github.com/pulumi/pulumi-spotinst/sdk/go/spotinst/aws?tab=doc#ElastigroupIntegrationCodedeployArgs">input</a> and <a href="https://pkg.go.dev/github.com/pulumi/pulumi-spotinst/sdk/go/spotinst/aws?tab=doc#ElastigroupIntegrationCodedeployOutput">output</a> API doc for this type.
{{% /choosable %}}




{{% choosable language csharp %}}
<dl class="resources-properties">

    <dt class="property-required"
            title="Required">
        <span>Cleanup<wbr>On<wbr>Failure</span>
        <span class="property-indicator"></span>
        <span class="property-type">bool</span>
    </dt>
    <dd>{{% md %}}{{% /md %}}</dd>

    <dt class="property-required"
            title="Required">
        <span>Deployment<wbr>Groups</span>
        <span class="property-indicator"></span>
        <span class="property-type"><a href="#elastigroupintegrationcodedeploydeploymentgroup">List&lt;Elastigroup<wbr>Integration<wbr>Codedeploy<wbr>Deployment<wbr>Group<wbr>Args&gt;</a></span>
    </dt>
    <dd>{{% md %}}{{% /md %}}</dd>

    <dt class="property-required"
            title="Required">
        <span>Terminate<wbr>Instance<wbr>On<wbr>Failure</span>
        <span class="property-indicator"></span>
        <span class="property-type">bool</span>
    </dt>
    <dd>{{% md %}}{{% /md %}}</dd>

</dl>
{{% /choosable %}}


{{% choosable language go %}}
<dl class="resources-properties">

    <dt class="property-required"
            title="Required">
        <span>Cleanup<wbr>On<wbr>Failure</span>
        <span class="property-indicator"></span>
        <span class="property-type">bool</span>
    </dt>
    <dd>{{% md %}}{{% /md %}}</dd>

    <dt class="property-required"
            title="Required">
        <span>Deployment<wbr>Groups</span>
        <span class="property-indicator"></span>
        <span class="property-type"><a href="#elastigroupintegrationcodedeploydeploymentgroup">[]Elastigroup<wbr>Integration<wbr>Codedeploy<wbr>Deployment<wbr>Group</a></span>
    </dt>
    <dd>{{% md %}}{{% /md %}}</dd>

    <dt class="property-required"
            title="Required">
        <span>Terminate<wbr>Instance<wbr>On<wbr>Failure</span>
        <span class="property-indicator"></span>
        <span class="property-type">bool</span>
    </dt>
    <dd>{{% md %}}{{% /md %}}</dd>

</dl>
{{% /choosable %}}


{{% choosable language nodejs %}}
<dl class="resources-properties">

    <dt class="property-required"
            title="Required">
        <span>cleanup<wbr>On<wbr>Failure</span>
        <span class="property-indicator"></span>
        <span class="property-type">boolean</span>
    </dt>
    <dd>{{% md %}}{{% /md %}}</dd>

    <dt class="property-required"
            title="Required">
        <span>deployment<wbr>Groups</span>
        <span class="property-indicator"></span>
        <span class="property-type"><a href="#elastigroupintegrationcodedeploydeploymentgroup">Elastigroup<wbr>Integration<wbr>Codedeploy<wbr>Deployment<wbr>Group[]</a></span>
    </dt>
    <dd>{{% md %}}{{% /md %}}</dd>

    <dt class="property-required"
            title="Required">
        <span>terminate<wbr>Instance<wbr>On<wbr>Failure</span>
        <span class="property-indicator"></span>
        <span class="property-type">boolean</span>
    </dt>
    <dd>{{% md %}}{{% /md %}}</dd>

</dl>
{{% /choosable %}}


{{% choosable language python %}}
<dl class="resources-properties">

    <dt class="property-required"
            title="Required">
        <span>cleanup<wbr>On<wbr>Failure</span>
        <span class="property-indicator"></span>
        <span class="property-type">bool</span>
    </dt>
    <dd>{{% md %}}{{% /md %}}</dd>

    <dt class="property-required"
            title="Required">
        <span>deployment<wbr>Groups</span>
        <span class="property-indicator"></span>
        <span class="property-type"><a href="#elastigroupintegrationcodedeploydeploymentgroup">List[Elastigroup<wbr>Integration<wbr>Codedeploy<wbr>Deployment<wbr>Group]</a></span>
    </dt>
    <dd>{{% md %}}{{% /md %}}</dd>

    <dt class="property-required"
            title="Required">
        <span>terminate<wbr>Instance<wbr>On<wbr>Failure</span>
        <span class="property-indicator"></span>
        <span class="property-type">bool</span>
    </dt>
    <dd>{{% md %}}{{% /md %}}</dd>

</dl>
{{% /choosable %}}





<h4>Elastigroup<wbr>Integration<wbr>Codedeploy<wbr>Deployment<wbr>Group</h4>
{{% choosable language nodejs %}}
> See the <a href="/docs/reference/pkg/nodejs/pulumi/spotinst/types/input/#ElastigroupIntegrationCodedeployDeploymentGroup">input</a> and <a href="/docs/reference/pkg/nodejs/pulumi/spotinst/types/output/#ElastigroupIntegrationCodedeployDeploymentGroup">output</a> API doc for this type.
{{% /choosable %}}

{{% choosable language go %}}
> See the <a href="https://pkg.go.dev/github.com/pulumi/pulumi-spotinst/sdk/go/spotinst/aws?tab=doc#ElastigroupIntegrationCodedeployDeploymentGroupArgs">input</a> and <a href="https://pkg.go.dev/github.com/pulumi/pulumi-spotinst/sdk/go/spotinst/aws?tab=doc#ElastigroupIntegrationCodedeployDeploymentGroupOutput">output</a> API doc for this type.
{{% /choosable %}}




{{% choosable language csharp %}}
<dl class="resources-properties">

    <dt class="property-required"
            title="Required">
        <span>Application<wbr>Name</span>
        <span class="property-indicator"></span>
        <span class="property-type">string</span>
    </dt>
    <dd>{{% md %}}{{% /md %}}</dd>

    <dt class="property-required"
            title="Required">
        <span>Deployment<wbr>Group<wbr>Name</span>
        <span class="property-indicator"></span>
        <span class="property-type">string</span>
    </dt>
    <dd>{{% md %}}{{% /md %}}</dd>

</dl>
{{% /choosable %}}


{{% choosable language go %}}
<dl class="resources-properties">

    <dt class="property-required"
            title="Required">
        <span>Application<wbr>Name</span>
        <span class="property-indicator"></span>
        <span class="property-type">string</span>
    </dt>
    <dd>{{% md %}}{{% /md %}}</dd>

    <dt class="property-required"
            title="Required">
        <span>Deployment<wbr>Group<wbr>Name</span>
        <span class="property-indicator"></span>
        <span class="property-type">string</span>
    </dt>
    <dd>{{% md %}}{{% /md %}}</dd>

</dl>
{{% /choosable %}}


{{% choosable language nodejs %}}
<dl class="resources-properties">

    <dt class="property-required"
            title="Required">
        <span>application<wbr>Name</span>
        <span class="property-indicator"></span>
        <span class="property-type">string</span>
    </dt>
    <dd>{{% md %}}{{% /md %}}</dd>

    <dt class="property-required"
            title="Required">
        <span>deployment<wbr>Group<wbr>Name</span>
        <span class="property-indicator"></span>
        <span class="property-type">string</span>
    </dt>
    <dd>{{% md %}}{{% /md %}}</dd>

</dl>
{{% /choosable %}}


{{% choosable language python %}}
<dl class="resources-properties">

    <dt class="property-required"
            title="Required">
        <span>application<wbr>Name</span>
        <span class="property-indicator"></span>
        <span class="property-type">str</span>
    </dt>
    <dd>{{% md %}}{{% /md %}}</dd>

    <dt class="property-required"
            title="Required">
        <span>deployment<wbr>Group<wbr>Name</span>
        <span class="property-indicator"></span>
        <span class="property-type">str</span>
    </dt>
    <dd>{{% md %}}{{% /md %}}</dd>

</dl>
{{% /choosable %}}





<h4>Elastigroup<wbr>Integration<wbr>Docker<wbr>Swarm</h4>
{{% choosable language nodejs %}}
> See the <a href="/docs/reference/pkg/nodejs/pulumi/spotinst/types/input/#ElastigroupIntegrationDockerSwarm">input</a> and <a href="/docs/reference/pkg/nodejs/pulumi/spotinst/types/output/#ElastigroupIntegrationDockerSwarm">output</a> API doc for this type.
{{% /choosable %}}

{{% choosable language go %}}
> See the <a href="https://pkg.go.dev/github.com/pulumi/pulumi-spotinst/sdk/go/spotinst/aws?tab=doc#ElastigroupIntegrationDockerSwarmArgs">input</a> and <a href="https://pkg.go.dev/github.com/pulumi/pulumi-spotinst/sdk/go/spotinst/aws?tab=doc#ElastigroupIntegrationDockerSwarmOutput">output</a> API doc for this type.
{{% /choosable %}}




{{% choosable language csharp %}}
<dl class="resources-properties">

    <dt class="property-optional"
            title="Optional">
        <span>Autoscale<wbr>Cooldown</span>
        <span class="property-indicator"></span>
        <span class="property-type">int?</span>
    </dt>
    <dd>{{% md %}}{{% /md %}}</dd>

    <dt class="property-optional"
            title="Optional">
        <span>Autoscale<wbr>Down</span>
        <span class="property-indicator"></span>
        <span class="property-type"><a href="#elastigroupintegrationdockerswarmautoscaledown">Elastigroup<wbr>Integration<wbr>Docker<wbr>Swarm<wbr>Autoscale<wbr>Down<wbr>Args?</a></span>
    </dt>
    <dd>{{% md %}}{{% /md %}}</dd>

    <dt class="property-optional"
            title="Optional">
        <span>Autoscale<wbr>Headroom</span>
        <span class="property-indicator"></span>
        <span class="property-type"><a href="#elastigroupintegrationdockerswarmautoscaleheadroom">Elastigroup<wbr>Integration<wbr>Docker<wbr>Swarm<wbr>Autoscale<wbr>Headroom<wbr>Args?</a></span>
    </dt>
    <dd>{{% md %}}{{% /md %}}</dd>

    <dt class="property-optional"
            title="Optional">
        <span>Autoscale<wbr>Is<wbr>Enabled</span>
        <span class="property-indicator"></span>
        <span class="property-type">bool?</span>
    </dt>
    <dd>{{% md %}}{{% /md %}}</dd>

    <dt class="property-required"
            title="Required">
        <span>Master<wbr>Host</span>
        <span class="property-indicator"></span>
        <span class="property-type">string</span>
    </dt>
    <dd>{{% md %}}{{% /md %}}</dd>

    <dt class="property-required"
            title="Required">
        <span>Master<wbr>Port</span>
        <span class="property-indicator"></span>
        <span class="property-type">int</span>
    </dt>
    <dd>{{% md %}}{{% /md %}}</dd>

</dl>
{{% /choosable %}}


{{% choosable language go %}}
<dl class="resources-properties">

    <dt class="property-optional"
            title="Optional">
        <span>Autoscale<wbr>Cooldown</span>
        <span class="property-indicator"></span>
        <span class="property-type">*int</span>
    </dt>
    <dd>{{% md %}}{{% /md %}}</dd>

    <dt class="property-optional"
            title="Optional">
        <span>Autoscale<wbr>Down</span>
        <span class="property-indicator"></span>
        <span class="property-type"><a href="#elastigroupintegrationdockerswarmautoscaledown">*Elastigroup<wbr>Integration<wbr>Docker<wbr>Swarm<wbr>Autoscale<wbr>Down</a></span>
    </dt>
    <dd>{{% md %}}{{% /md %}}</dd>

    <dt class="property-optional"
            title="Optional">
        <span>Autoscale<wbr>Headroom</span>
        <span class="property-indicator"></span>
        <span class="property-type"><a href="#elastigroupintegrationdockerswarmautoscaleheadroom">*Elastigroup<wbr>Integration<wbr>Docker<wbr>Swarm<wbr>Autoscale<wbr>Headroom</a></span>
    </dt>
    <dd>{{% md %}}{{% /md %}}</dd>

    <dt class="property-optional"
            title="Optional">
        <span>Autoscale<wbr>Is<wbr>Enabled</span>
        <span class="property-indicator"></span>
        <span class="property-type">*bool</span>
    </dt>
    <dd>{{% md %}}{{% /md %}}</dd>

    <dt class="property-required"
            title="Required">
        <span>Master<wbr>Host</span>
        <span class="property-indicator"></span>
        <span class="property-type">string</span>
    </dt>
    <dd>{{% md %}}{{% /md %}}</dd>

    <dt class="property-required"
            title="Required">
        <span>Master<wbr>Port</span>
        <span class="property-indicator"></span>
        <span class="property-type">int</span>
    </dt>
    <dd>{{% md %}}{{% /md %}}</dd>

</dl>
{{% /choosable %}}


{{% choosable language nodejs %}}
<dl class="resources-properties">

    <dt class="property-optional"
            title="Optional">
        <span>autoscale<wbr>Cooldown</span>
        <span class="property-indicator"></span>
        <span class="property-type">number?</span>
    </dt>
    <dd>{{% md %}}{{% /md %}}</dd>

    <dt class="property-optional"
            title="Optional">
        <span>autoscale<wbr>Down</span>
        <span class="property-indicator"></span>
        <span class="property-type"><a href="#elastigroupintegrationdockerswarmautoscaledown">Elastigroup<wbr>Integration<wbr>Docker<wbr>Swarm<wbr>Autoscale<wbr>Down?</a></span>
    </dt>
    <dd>{{% md %}}{{% /md %}}</dd>

    <dt class="property-optional"
            title="Optional">
        <span>autoscale<wbr>Headroom</span>
        <span class="property-indicator"></span>
        <span class="property-type"><a href="#elastigroupintegrationdockerswarmautoscaleheadroom">Elastigroup<wbr>Integration<wbr>Docker<wbr>Swarm<wbr>Autoscale<wbr>Headroom?</a></span>
    </dt>
    <dd>{{% md %}}{{% /md %}}</dd>

    <dt class="property-optional"
            title="Optional">
        <span>autoscale<wbr>Is<wbr>Enabled</span>
        <span class="property-indicator"></span>
        <span class="property-type">boolean?</span>
    </dt>
    <dd>{{% md %}}{{% /md %}}</dd>

    <dt class="property-required"
            title="Required">
        <span>master<wbr>Host</span>
        <span class="property-indicator"></span>
        <span class="property-type">string</span>
    </dt>
    <dd>{{% md %}}{{% /md %}}</dd>

    <dt class="property-required"
            title="Required">
        <span>master<wbr>Port</span>
        <span class="property-indicator"></span>
        <span class="property-type">number</span>
    </dt>
    <dd>{{% md %}}{{% /md %}}</dd>

</dl>
{{% /choosable %}}


{{% choosable language python %}}
<dl class="resources-properties">

    <dt class="property-optional"
            title="Optional">
        <span>autoscale<wbr>Cooldown</span>
        <span class="property-indicator"></span>
        <span class="property-type">float</span>
    </dt>
    <dd>{{% md %}}{{% /md %}}</dd>

    <dt class="property-optional"
            title="Optional">
        <span>autoscale<wbr>Down</span>
        <span class="property-indicator"></span>
        <span class="property-type"><a href="#elastigroupintegrationdockerswarmautoscaledown">Dict[Elastigroup<wbr>Integration<wbr>Docker<wbr>Swarm<wbr>Autoscale<wbr>Down]</a></span>
    </dt>
    <dd>{{% md %}}{{% /md %}}</dd>

    <dt class="property-optional"
            title="Optional">
        <span>autoscale<wbr>Headroom</span>
        <span class="property-indicator"></span>
        <span class="property-type"><a href="#elastigroupintegrationdockerswarmautoscaleheadroom">Dict[Elastigroup<wbr>Integration<wbr>Docker<wbr>Swarm<wbr>Autoscale<wbr>Headroom]</a></span>
    </dt>
    <dd>{{% md %}}{{% /md %}}</dd>

    <dt class="property-optional"
            title="Optional">
        <span>autoscale<wbr>Is<wbr>Enabled</span>
        <span class="property-indicator"></span>
        <span class="property-type">bool</span>
    </dt>
    <dd>{{% md %}}{{% /md %}}</dd>

    <dt class="property-required"
            title="Required">
        <span>master<wbr>Host</span>
        <span class="property-indicator"></span>
        <span class="property-type">str</span>
    </dt>
    <dd>{{% md %}}{{% /md %}}</dd>

    <dt class="property-required"
            title="Required">
        <span>master<wbr>Port</span>
        <span class="property-indicator"></span>
        <span class="property-type">float</span>
    </dt>
    <dd>{{% md %}}{{% /md %}}</dd>

</dl>
{{% /choosable %}}





<h4>Elastigroup<wbr>Integration<wbr>Docker<wbr>Swarm<wbr>Autoscale<wbr>Down</h4>
{{% choosable language nodejs %}}
> See the <a href="/docs/reference/pkg/nodejs/pulumi/spotinst/types/input/#ElastigroupIntegrationDockerSwarmAutoscaleDown">input</a> and <a href="/docs/reference/pkg/nodejs/pulumi/spotinst/types/output/#ElastigroupIntegrationDockerSwarmAutoscaleDown">output</a> API doc for this type.
{{% /choosable %}}

{{% choosable language go %}}
> See the <a href="https://pkg.go.dev/github.com/pulumi/pulumi-spotinst/sdk/go/spotinst/aws?tab=doc#ElastigroupIntegrationDockerSwarmAutoscaleDownArgs">input</a> and <a href="https://pkg.go.dev/github.com/pulumi/pulumi-spotinst/sdk/go/spotinst/aws?tab=doc#ElastigroupIntegrationDockerSwarmAutoscaleDownOutput">output</a> API doc for this type.
{{% /choosable %}}




{{% choosable language csharp %}}
<dl class="resources-properties">

    <dt class="property-optional"
            title="Optional">
        <span>Evaluation<wbr>Periods</span>
        <span class="property-indicator"></span>
        <span class="property-type">int?</span>
    </dt>
    <dd>{{% md %}}{{% /md %}}</dd>

</dl>
{{% /choosable %}}


{{% choosable language go %}}
<dl class="resources-properties">

    <dt class="property-optional"
            title="Optional">
        <span>Evaluation<wbr>Periods</span>
        <span class="property-indicator"></span>
        <span class="property-type">*int</span>
    </dt>
    <dd>{{% md %}}{{% /md %}}</dd>

</dl>
{{% /choosable %}}


{{% choosable language nodejs %}}
<dl class="resources-properties">

    <dt class="property-optional"
            title="Optional">
        <span>evaluation<wbr>Periods</span>
        <span class="property-indicator"></span>
        <span class="property-type">number?</span>
    </dt>
    <dd>{{% md %}}{{% /md %}}</dd>

</dl>
{{% /choosable %}}


{{% choosable language python %}}
<dl class="resources-properties">

    <dt class="property-optional"
            title="Optional">
        <span>evaluation<wbr>Periods</span>
        <span class="property-indicator"></span>
        <span class="property-type">float</span>
    </dt>
    <dd>{{% md %}}{{% /md %}}</dd>

</dl>
{{% /choosable %}}





<h4>Elastigroup<wbr>Integration<wbr>Docker<wbr>Swarm<wbr>Autoscale<wbr>Headroom</h4>
{{% choosable language nodejs %}}
> See the <a href="/docs/reference/pkg/nodejs/pulumi/spotinst/types/input/#ElastigroupIntegrationDockerSwarmAutoscaleHeadroom">input</a> and <a href="/docs/reference/pkg/nodejs/pulumi/spotinst/types/output/#ElastigroupIntegrationDockerSwarmAutoscaleHeadroom">output</a> API doc for this type.
{{% /choosable %}}

{{% choosable language go %}}
> See the <a href="https://pkg.go.dev/github.com/pulumi/pulumi-spotinst/sdk/go/spotinst/aws?tab=doc#ElastigroupIntegrationDockerSwarmAutoscaleHeadroomArgs">input</a> and <a href="https://pkg.go.dev/github.com/pulumi/pulumi-spotinst/sdk/go/spotinst/aws?tab=doc#ElastigroupIntegrationDockerSwarmAutoscaleHeadroomOutput">output</a> API doc for this type.
{{% /choosable %}}




{{% choosable language csharp %}}
<dl class="resources-properties">

    <dt class="property-optional"
            title="Optional">
        <span>Cpu<wbr>Per<wbr>Unit</span>
        <span class="property-indicator"></span>
        <span class="property-type">int?</span>
    </dt>
    <dd>{{% md %}}{{% /md %}}</dd>

    <dt class="property-optional"
            title="Optional">
        <span>Memory<wbr>Per<wbr>Unit</span>
        <span class="property-indicator"></span>
        <span class="property-type">int?</span>
    </dt>
    <dd>{{% md %}}{{% /md %}}</dd>

    <dt class="property-optional"
            title="Optional">
        <span>Num<wbr>Of<wbr>Units</span>
        <span class="property-indicator"></span>
        <span class="property-type">int?</span>
    </dt>
    <dd>{{% md %}}{{% /md %}}</dd>

</dl>
{{% /choosable %}}


{{% choosable language go %}}
<dl class="resources-properties">

    <dt class="property-optional"
            title="Optional">
        <span>Cpu<wbr>Per<wbr>Unit</span>
        <span class="property-indicator"></span>
        <span class="property-type">*int</span>
    </dt>
    <dd>{{% md %}}{{% /md %}}</dd>

    <dt class="property-optional"
            title="Optional">
        <span>Memory<wbr>Per<wbr>Unit</span>
        <span class="property-indicator"></span>
        <span class="property-type">*int</span>
    </dt>
    <dd>{{% md %}}{{% /md %}}</dd>

    <dt class="property-optional"
            title="Optional">
        <span>Num<wbr>Of<wbr>Units</span>
        <span class="property-indicator"></span>
        <span class="property-type">*int</span>
    </dt>
    <dd>{{% md %}}{{% /md %}}</dd>

</dl>
{{% /choosable %}}


{{% choosable language nodejs %}}
<dl class="resources-properties">

    <dt class="property-optional"
            title="Optional">
        <span>cpu<wbr>Per<wbr>Unit</span>
        <span class="property-indicator"></span>
        <span class="property-type">number?</span>
    </dt>
    <dd>{{% md %}}{{% /md %}}</dd>

    <dt class="property-optional"
            title="Optional">
        <span>memory<wbr>Per<wbr>Unit</span>
        <span class="property-indicator"></span>
        <span class="property-type">number?</span>
    </dt>
    <dd>{{% md %}}{{% /md %}}</dd>

    <dt class="property-optional"
            title="Optional">
        <span>num<wbr>Of<wbr>Units</span>
        <span class="property-indicator"></span>
        <span class="property-type">number?</span>
    </dt>
    <dd>{{% md %}}{{% /md %}}</dd>

</dl>
{{% /choosable %}}


{{% choosable language python %}}
<dl class="resources-properties">

    <dt class="property-optional"
            title="Optional">
        <span>cpu<wbr>Per<wbr>Unit</span>
        <span class="property-indicator"></span>
        <span class="property-type">float</span>
    </dt>
    <dd>{{% md %}}{{% /md %}}</dd>

    <dt class="property-optional"
            title="Optional">
        <span>memory<wbr>Per<wbr>Unit</span>
        <span class="property-indicator"></span>
        <span class="property-type">float</span>
    </dt>
    <dd>{{% md %}}{{% /md %}}</dd>

    <dt class="property-optional"
            title="Optional">
        <span>num<wbr>Of<wbr>Units</span>
        <span class="property-indicator"></span>
        <span class="property-type">float</span>
    </dt>
    <dd>{{% md %}}{{% /md %}}</dd>

</dl>
{{% /choosable %}}





<h4>Elastigroup<wbr>Integration<wbr>Ecs</h4>
{{% choosable language nodejs %}}
> See the <a href="/docs/reference/pkg/nodejs/pulumi/spotinst/types/input/#ElastigroupIntegrationEcs">input</a> and <a href="/docs/reference/pkg/nodejs/pulumi/spotinst/types/output/#ElastigroupIntegrationEcs">output</a> API doc for this type.
{{% /choosable %}}

{{% choosable language go %}}
> See the <a href="https://pkg.go.dev/github.com/pulumi/pulumi-spotinst/sdk/go/spotinst/aws?tab=doc#ElastigroupIntegrationEcsArgs">input</a> and <a href="https://pkg.go.dev/github.com/pulumi/pulumi-spotinst/sdk/go/spotinst/aws?tab=doc#ElastigroupIntegrationEcsOutput">output</a> API doc for this type.
{{% /choosable %}}




{{% choosable language csharp %}}
<dl class="resources-properties">

    <dt class="property-optional"
            title="Optional">
        <span>Autoscale<wbr>Attributes</span>
        <span class="property-indicator"></span>
        <span class="property-type"><a href="#elastigroupintegrationecsautoscaleattribute">List&lt;Elastigroup<wbr>Integration<wbr>Ecs<wbr>Autoscale<wbr>Attribute<wbr>Args&gt;?</a></span>
    </dt>
    <dd>{{% md %}}{{% /md %}}</dd>

    <dt class="property-optional"
            title="Optional">
        <span>Autoscale<wbr>Cooldown</span>
        <span class="property-indicator"></span>
        <span class="property-type">int?</span>
    </dt>
    <dd>{{% md %}}{{% /md %}}</dd>

    <dt class="property-optional"
            title="Optional">
        <span>Autoscale<wbr>Down</span>
        <span class="property-indicator"></span>
        <span class="property-type"><a href="#elastigroupintegrationecsautoscaledown">Elastigroup<wbr>Integration<wbr>Ecs<wbr>Autoscale<wbr>Down<wbr>Args?</a></span>
    </dt>
    <dd>{{% md %}}{{% /md %}}</dd>

    <dt class="property-optional"
            title="Optional">
        <span>Autoscale<wbr>Headroom</span>
        <span class="property-indicator"></span>
        <span class="property-type"><a href="#elastigroupintegrationecsautoscaleheadroom">Elastigroup<wbr>Integration<wbr>Ecs<wbr>Autoscale<wbr>Headroom<wbr>Args?</a></span>
    </dt>
    <dd>{{% md %}}{{% /md %}}</dd>

    <dt class="property-optional"
            title="Optional">
        <span>Autoscale<wbr>Is<wbr>Auto<wbr>Config</span>
        <span class="property-indicator"></span>
        <span class="property-type">bool?</span>
    </dt>
    <dd>{{% md %}}{{% /md %}}</dd>

    <dt class="property-optional"
            title="Optional">
        <span>Autoscale<wbr>Is<wbr>Enabled</span>
        <span class="property-indicator"></span>
        <span class="property-type">bool?</span>
    </dt>
    <dd>{{% md %}}{{% /md %}}</dd>

    <dt class="property-optional"
            title="Optional">
        <span>Autoscale<wbr>Scale<wbr>Down<wbr>Non<wbr>Service<wbr>Tasks</span>
        <span class="property-indicator"></span>
        <span class="property-type">bool?</span>
    </dt>
    <dd>{{% md %}}{{% /md %}}</dd>

    <dt class="property-required"
            title="Required">
        <span>Cluster<wbr>Name</span>
        <span class="property-indicator"></span>
        <span class="property-type">string</span>
    </dt>
    <dd>{{% md %}}{{% /md %}}</dd>

</dl>
{{% /choosable %}}


{{% choosable language go %}}
<dl class="resources-properties">

    <dt class="property-optional"
            title="Optional">
        <span>Autoscale<wbr>Attributes</span>
        <span class="property-indicator"></span>
        <span class="property-type"><a href="#elastigroupintegrationecsautoscaleattribute">[]Elastigroup<wbr>Integration<wbr>Ecs<wbr>Autoscale<wbr>Attribute</a></span>
    </dt>
    <dd>{{% md %}}{{% /md %}}</dd>

    <dt class="property-optional"
            title="Optional">
        <span>Autoscale<wbr>Cooldown</span>
        <span class="property-indicator"></span>
        <span class="property-type">*int</span>
    </dt>
    <dd>{{% md %}}{{% /md %}}</dd>

    <dt class="property-optional"
            title="Optional">
        <span>Autoscale<wbr>Down</span>
        <span class="property-indicator"></span>
        <span class="property-type"><a href="#elastigroupintegrationecsautoscaledown">*Elastigroup<wbr>Integration<wbr>Ecs<wbr>Autoscale<wbr>Down</a></span>
    </dt>
    <dd>{{% md %}}{{% /md %}}</dd>

    <dt class="property-optional"
            title="Optional">
        <span>Autoscale<wbr>Headroom</span>
        <span class="property-indicator"></span>
        <span class="property-type"><a href="#elastigroupintegrationecsautoscaleheadroom">*Elastigroup<wbr>Integration<wbr>Ecs<wbr>Autoscale<wbr>Headroom</a></span>
    </dt>
    <dd>{{% md %}}{{% /md %}}</dd>

    <dt class="property-optional"
            title="Optional">
        <span>Autoscale<wbr>Is<wbr>Auto<wbr>Config</span>
        <span class="property-indicator"></span>
        <span class="property-type">*bool</span>
    </dt>
    <dd>{{% md %}}{{% /md %}}</dd>

    <dt class="property-optional"
            title="Optional">
        <span>Autoscale<wbr>Is<wbr>Enabled</span>
        <span class="property-indicator"></span>
        <span class="property-type">*bool</span>
    </dt>
    <dd>{{% md %}}{{% /md %}}</dd>

    <dt class="property-optional"
            title="Optional">
        <span>Autoscale<wbr>Scale<wbr>Down<wbr>Non<wbr>Service<wbr>Tasks</span>
        <span class="property-indicator"></span>
        <span class="property-type">*bool</span>
    </dt>
    <dd>{{% md %}}{{% /md %}}</dd>

    <dt class="property-required"
            title="Required">
        <span>Cluster<wbr>Name</span>
        <span class="property-indicator"></span>
        <span class="property-type">string</span>
    </dt>
    <dd>{{% md %}}{{% /md %}}</dd>

</dl>
{{% /choosable %}}


{{% choosable language nodejs %}}
<dl class="resources-properties">

    <dt class="property-optional"
            title="Optional">
        <span>autoscale<wbr>Attributes</span>
        <span class="property-indicator"></span>
        <span class="property-type"><a href="#elastigroupintegrationecsautoscaleattribute">Elastigroup<wbr>Integration<wbr>Ecs<wbr>Autoscale<wbr>Attribute[]?</a></span>
    </dt>
    <dd>{{% md %}}{{% /md %}}</dd>

    <dt class="property-optional"
            title="Optional">
        <span>autoscale<wbr>Cooldown</span>
        <span class="property-indicator"></span>
        <span class="property-type">number?</span>
    </dt>
    <dd>{{% md %}}{{% /md %}}</dd>

    <dt class="property-optional"
            title="Optional">
        <span>autoscale<wbr>Down</span>
        <span class="property-indicator"></span>
        <span class="property-type"><a href="#elastigroupintegrationecsautoscaledown">Elastigroup<wbr>Integration<wbr>Ecs<wbr>Autoscale<wbr>Down?</a></span>
    </dt>
    <dd>{{% md %}}{{% /md %}}</dd>

    <dt class="property-optional"
            title="Optional">
        <span>autoscale<wbr>Headroom</span>
        <span class="property-indicator"></span>
        <span class="property-type"><a href="#elastigroupintegrationecsautoscaleheadroom">Elastigroup<wbr>Integration<wbr>Ecs<wbr>Autoscale<wbr>Headroom?</a></span>
    </dt>
    <dd>{{% md %}}{{% /md %}}</dd>

    <dt class="property-optional"
            title="Optional">
        <span>autoscale<wbr>Is<wbr>Auto<wbr>Config</span>
        <span class="property-indicator"></span>
        <span class="property-type">boolean?</span>
    </dt>
    <dd>{{% md %}}{{% /md %}}</dd>

    <dt class="property-optional"
            title="Optional">
        <span>autoscale<wbr>Is<wbr>Enabled</span>
        <span class="property-indicator"></span>
        <span class="property-type">boolean?</span>
    </dt>
    <dd>{{% md %}}{{% /md %}}</dd>

    <dt class="property-optional"
            title="Optional">
        <span>autoscale<wbr>Scale<wbr>Down<wbr>Non<wbr>Service<wbr>Tasks</span>
        <span class="property-indicator"></span>
        <span class="property-type">boolean?</span>
    </dt>
    <dd>{{% md %}}{{% /md %}}</dd>

    <dt class="property-required"
            title="Required">
        <span>cluster<wbr>Name</span>
        <span class="property-indicator"></span>
        <span class="property-type">string</span>
    </dt>
    <dd>{{% md %}}{{% /md %}}</dd>

</dl>
{{% /choosable %}}


{{% choosable language python %}}
<dl class="resources-properties">

    <dt class="property-optional"
            title="Optional">
        <span>autoscale<wbr>Attributes</span>
        <span class="property-indicator"></span>
        <span class="property-type"><a href="#elastigroupintegrationecsautoscaleattribute">List[Elastigroup<wbr>Integration<wbr>Ecs<wbr>Autoscale<wbr>Attribute]</a></span>
    </dt>
    <dd>{{% md %}}{{% /md %}}</dd>

    <dt class="property-optional"
            title="Optional">
        <span>autoscale<wbr>Cooldown</span>
        <span class="property-indicator"></span>
        <span class="property-type">float</span>
    </dt>
    <dd>{{% md %}}{{% /md %}}</dd>

    <dt class="property-optional"
            title="Optional">
        <span>autoscale<wbr>Down</span>
        <span class="property-indicator"></span>
        <span class="property-type"><a href="#elastigroupintegrationecsautoscaledown">Dict[Elastigroup<wbr>Integration<wbr>Ecs<wbr>Autoscale<wbr>Down]</a></span>
    </dt>
    <dd>{{% md %}}{{% /md %}}</dd>

    <dt class="property-optional"
            title="Optional">
        <span>autoscale<wbr>Headroom</span>
        <span class="property-indicator"></span>
        <span class="property-type"><a href="#elastigroupintegrationecsautoscaleheadroom">Dict[Elastigroup<wbr>Integration<wbr>Ecs<wbr>Autoscale<wbr>Headroom]</a></span>
    </dt>
    <dd>{{% md %}}{{% /md %}}</dd>

    <dt class="property-optional"
            title="Optional">
        <span>autoscale<wbr>Is<wbr>Auto<wbr>Config</span>
        <span class="property-indicator"></span>
        <span class="property-type">bool</span>
    </dt>
    <dd>{{% md %}}{{% /md %}}</dd>

    <dt class="property-optional"
            title="Optional">
        <span>autoscale<wbr>Is<wbr>Enabled</span>
        <span class="property-indicator"></span>
        <span class="property-type">bool</span>
    </dt>
    <dd>{{% md %}}{{% /md %}}</dd>

    <dt class="property-optional"
            title="Optional">
        <span>autoscale<wbr>Scale<wbr>Down<wbr>Non<wbr>Service<wbr>Tasks</span>
        <span class="property-indicator"></span>
        <span class="property-type">bool</span>
    </dt>
    <dd>{{% md %}}{{% /md %}}</dd>

    <dt class="property-required"
            title="Required">
        <span>cluster_<wbr>name</span>
        <span class="property-indicator"></span>
        <span class="property-type">str</span>
    </dt>
    <dd>{{% md %}}{{% /md %}}</dd>

</dl>
{{% /choosable %}}





<h4>Elastigroup<wbr>Integration<wbr>Ecs<wbr>Autoscale<wbr>Attribute</h4>
{{% choosable language nodejs %}}
> See the <a href="/docs/reference/pkg/nodejs/pulumi/spotinst/types/input/#ElastigroupIntegrationEcsAutoscaleAttribute">input</a> and <a href="/docs/reference/pkg/nodejs/pulumi/spotinst/types/output/#ElastigroupIntegrationEcsAutoscaleAttribute">output</a> API doc for this type.
{{% /choosable %}}

{{% choosable language go %}}
> See the <a href="https://pkg.go.dev/github.com/pulumi/pulumi-spotinst/sdk/go/spotinst/aws?tab=doc#ElastigroupIntegrationEcsAutoscaleAttributeArgs">input</a> and <a href="https://pkg.go.dev/github.com/pulumi/pulumi-spotinst/sdk/go/spotinst/aws?tab=doc#ElastigroupIntegrationEcsAutoscaleAttributeOutput">output</a> API doc for this type.
{{% /choosable %}}




{{% choosable language csharp %}}
<dl class="resources-properties">

    <dt class="property-required"
            title="Required">
        <span>Key</span>
        <span class="property-indicator"></span>
        <span class="property-type">string</span>
    </dt>
    <dd>{{% md %}}{{% /md %}}</dd>

    <dt class="property-required"
            title="Required">
        <span>Value</span>
        <span class="property-indicator"></span>
        <span class="property-type">string</span>
    </dt>
    <dd>{{% md %}}{{% /md %}}</dd>

</dl>
{{% /choosable %}}


{{% choosable language go %}}
<dl class="resources-properties">

    <dt class="property-required"
            title="Required">
        <span>Key</span>
        <span class="property-indicator"></span>
        <span class="property-type">string</span>
    </dt>
    <dd>{{% md %}}{{% /md %}}</dd>

    <dt class="property-required"
            title="Required">
        <span>Value</span>
        <span class="property-indicator"></span>
        <span class="property-type">string</span>
    </dt>
    <dd>{{% md %}}{{% /md %}}</dd>

</dl>
{{% /choosable %}}


{{% choosable language nodejs %}}
<dl class="resources-properties">

    <dt class="property-required"
            title="Required">
        <span>key</span>
        <span class="property-indicator"></span>
        <span class="property-type">string</span>
    </dt>
    <dd>{{% md %}}{{% /md %}}</dd>

    <dt class="property-required"
            title="Required">
        <span>value</span>
        <span class="property-indicator"></span>
        <span class="property-type">string</span>
    </dt>
    <dd>{{% md %}}{{% /md %}}</dd>

</dl>
{{% /choosable %}}


{{% choosable language python %}}
<dl class="resources-properties">

    <dt class="property-required"
            title="Required">
        <span>key</span>
        <span class="property-indicator"></span>
        <span class="property-type">str</span>
    </dt>
    <dd>{{% md %}}{{% /md %}}</dd>

    <dt class="property-required"
            title="Required">
        <span>value</span>
        <span class="property-indicator"></span>
        <span class="property-type">str</span>
    </dt>
    <dd>{{% md %}}{{% /md %}}</dd>

</dl>
{{% /choosable %}}





<h4>Elastigroup<wbr>Integration<wbr>Ecs<wbr>Autoscale<wbr>Down</h4>
{{% choosable language nodejs %}}
> See the <a href="/docs/reference/pkg/nodejs/pulumi/spotinst/types/input/#ElastigroupIntegrationEcsAutoscaleDown">input</a> and <a href="/docs/reference/pkg/nodejs/pulumi/spotinst/types/output/#ElastigroupIntegrationEcsAutoscaleDown">output</a> API doc for this type.
{{% /choosable %}}

{{% choosable language go %}}
> See the <a href="https://pkg.go.dev/github.com/pulumi/pulumi-spotinst/sdk/go/spotinst/aws?tab=doc#ElastigroupIntegrationEcsAutoscaleDownArgs">input</a> and <a href="https://pkg.go.dev/github.com/pulumi/pulumi-spotinst/sdk/go/spotinst/aws?tab=doc#ElastigroupIntegrationEcsAutoscaleDownOutput">output</a> API doc for this type.
{{% /choosable %}}




{{% choosable language csharp %}}
<dl class="resources-properties">

    <dt class="property-optional"
            title="Optional">
        <span>Evaluation<wbr>Periods</span>
        <span class="property-indicator"></span>
        <span class="property-type">int?</span>
    </dt>
    <dd>{{% md %}}{{% /md %}}</dd>

    <dt class="property-optional"
            title="Optional">
        <span>Max<wbr>Scale<wbr>Down<wbr>Percentage</span>
        <span class="property-indicator"></span>
        <span class="property-type">int?</span>
    </dt>
    <dd>{{% md %}}{{% /md %}}</dd>

</dl>
{{% /choosable %}}


{{% choosable language go %}}
<dl class="resources-properties">

    <dt class="property-optional"
            title="Optional">
        <span>Evaluation<wbr>Periods</span>
        <span class="property-indicator"></span>
        <span class="property-type">*int</span>
    </dt>
    <dd>{{% md %}}{{% /md %}}</dd>

    <dt class="property-optional"
            title="Optional">
        <span>Max<wbr>Scale<wbr>Down<wbr>Percentage</span>
        <span class="property-indicator"></span>
        <span class="property-type">*int</span>
    </dt>
    <dd>{{% md %}}{{% /md %}}</dd>

</dl>
{{% /choosable %}}


{{% choosable language nodejs %}}
<dl class="resources-properties">

    <dt class="property-optional"
            title="Optional">
        <span>evaluation<wbr>Periods</span>
        <span class="property-indicator"></span>
        <span class="property-type">number?</span>
    </dt>
    <dd>{{% md %}}{{% /md %}}</dd>

    <dt class="property-optional"
            title="Optional">
        <span>max<wbr>Scale<wbr>Down<wbr>Percentage</span>
        <span class="property-indicator"></span>
        <span class="property-type">number?</span>
    </dt>
    <dd>{{% md %}}{{% /md %}}</dd>

</dl>
{{% /choosable %}}


{{% choosable language python %}}
<dl class="resources-properties">

    <dt class="property-optional"
            title="Optional">
        <span>evaluation<wbr>Periods</span>
        <span class="property-indicator"></span>
        <span class="property-type">float</span>
    </dt>
    <dd>{{% md %}}{{% /md %}}</dd>

    <dt class="property-optional"
            title="Optional">
        <span>max<wbr>Scale<wbr>Down<wbr>Percentage</span>
        <span class="property-indicator"></span>
        <span class="property-type">float</span>
    </dt>
    <dd>{{% md %}}{{% /md %}}</dd>

</dl>
{{% /choosable %}}





<h4>Elastigroup<wbr>Integration<wbr>Ecs<wbr>Autoscale<wbr>Headroom</h4>
{{% choosable language nodejs %}}
> See the <a href="/docs/reference/pkg/nodejs/pulumi/spotinst/types/input/#ElastigroupIntegrationEcsAutoscaleHeadroom">input</a> and <a href="/docs/reference/pkg/nodejs/pulumi/spotinst/types/output/#ElastigroupIntegrationEcsAutoscaleHeadroom">output</a> API doc for this type.
{{% /choosable %}}

{{% choosable language go %}}
> See the <a href="https://pkg.go.dev/github.com/pulumi/pulumi-spotinst/sdk/go/spotinst/aws?tab=doc#ElastigroupIntegrationEcsAutoscaleHeadroomArgs">input</a> and <a href="https://pkg.go.dev/github.com/pulumi/pulumi-spotinst/sdk/go/spotinst/aws?tab=doc#ElastigroupIntegrationEcsAutoscaleHeadroomOutput">output</a> API doc for this type.
{{% /choosable %}}




{{% choosable language csharp %}}
<dl class="resources-properties">

    <dt class="property-optional"
            title="Optional">
        <span>Cpu<wbr>Per<wbr>Unit</span>
        <span class="property-indicator"></span>
        <span class="property-type">int?</span>
    </dt>
    <dd>{{% md %}}{{% /md %}}</dd>

    <dt class="property-optional"
            title="Optional">
        <span>Memory<wbr>Per<wbr>Unit</span>
        <span class="property-indicator"></span>
        <span class="property-type">int?</span>
    </dt>
    <dd>{{% md %}}{{% /md %}}</dd>

    <dt class="property-optional"
            title="Optional">
        <span>Num<wbr>Of<wbr>Units</span>
        <span class="property-indicator"></span>
        <span class="property-type">int?</span>
    </dt>
    <dd>{{% md %}}{{% /md %}}</dd>

</dl>
{{% /choosable %}}


{{% choosable language go %}}
<dl class="resources-properties">

    <dt class="property-optional"
            title="Optional">
        <span>Cpu<wbr>Per<wbr>Unit</span>
        <span class="property-indicator"></span>
        <span class="property-type">*int</span>
    </dt>
    <dd>{{% md %}}{{% /md %}}</dd>

    <dt class="property-optional"
            title="Optional">
        <span>Memory<wbr>Per<wbr>Unit</span>
        <span class="property-indicator"></span>
        <span class="property-type">*int</span>
    </dt>
    <dd>{{% md %}}{{% /md %}}</dd>

    <dt class="property-optional"
            title="Optional">
        <span>Num<wbr>Of<wbr>Units</span>
        <span class="property-indicator"></span>
        <span class="property-type">*int</span>
    </dt>
    <dd>{{% md %}}{{% /md %}}</dd>

</dl>
{{% /choosable %}}


{{% choosable language nodejs %}}
<dl class="resources-properties">

    <dt class="property-optional"
            title="Optional">
        <span>cpu<wbr>Per<wbr>Unit</span>
        <span class="property-indicator"></span>
        <span class="property-type">number?</span>
    </dt>
    <dd>{{% md %}}{{% /md %}}</dd>

    <dt class="property-optional"
            title="Optional">
        <span>memory<wbr>Per<wbr>Unit</span>
        <span class="property-indicator"></span>
        <span class="property-type">number?</span>
    </dt>
    <dd>{{% md %}}{{% /md %}}</dd>

    <dt class="property-optional"
            title="Optional">
        <span>num<wbr>Of<wbr>Units</span>
        <span class="property-indicator"></span>
        <span class="property-type">number?</span>
    </dt>
    <dd>{{% md %}}{{% /md %}}</dd>

</dl>
{{% /choosable %}}


{{% choosable language python %}}
<dl class="resources-properties">

    <dt class="property-optional"
            title="Optional">
        <span>cpu<wbr>Per<wbr>Unit</span>
        <span class="property-indicator"></span>
        <span class="property-type">float</span>
    </dt>
    <dd>{{% md %}}{{% /md %}}</dd>

    <dt class="property-optional"
            title="Optional">
        <span>memory<wbr>Per<wbr>Unit</span>
        <span class="property-indicator"></span>
        <span class="property-type">float</span>
    </dt>
    <dd>{{% md %}}{{% /md %}}</dd>

    <dt class="property-optional"
            title="Optional">
        <span>num<wbr>Of<wbr>Units</span>
        <span class="property-indicator"></span>
        <span class="property-type">float</span>
    </dt>
    <dd>{{% md %}}{{% /md %}}</dd>

</dl>
{{% /choosable %}}





<h4>Elastigroup<wbr>Integration<wbr>Gitlab</h4>
{{% choosable language nodejs %}}
> See the <a href="/docs/reference/pkg/nodejs/pulumi/spotinst/types/input/#ElastigroupIntegrationGitlab">input</a> and <a href="/docs/reference/pkg/nodejs/pulumi/spotinst/types/output/#ElastigroupIntegrationGitlab">output</a> API doc for this type.
{{% /choosable %}}

{{% choosable language go %}}
> See the <a href="https://pkg.go.dev/github.com/pulumi/pulumi-spotinst/sdk/go/spotinst/aws?tab=doc#ElastigroupIntegrationGitlabArgs">input</a> and <a href="https://pkg.go.dev/github.com/pulumi/pulumi-spotinst/sdk/go/spotinst/aws?tab=doc#ElastigroupIntegrationGitlabOutput">output</a> API doc for this type.
{{% /choosable %}}




{{% choosable language csharp %}}
<dl class="resources-properties">

    <dt class="property-optional"
            title="Optional">
        <span>Runner</span>
        <span class="property-indicator"></span>
        <span class="property-type"><a href="#elastigroupintegrationgitlabrunner">Elastigroup<wbr>Integration<wbr>Gitlab<wbr>Runner<wbr>Args?</a></span>
    </dt>
    <dd>{{% md %}}{{% /md %}}</dd>

</dl>
{{% /choosable %}}


{{% choosable language go %}}
<dl class="resources-properties">

    <dt class="property-optional"
            title="Optional">
        <span>Runner</span>
        <span class="property-indicator"></span>
        <span class="property-type"><a href="#elastigroupintegrationgitlabrunner">*Elastigroup<wbr>Integration<wbr>Gitlab<wbr>Runner</a></span>
    </dt>
    <dd>{{% md %}}{{% /md %}}</dd>

</dl>
{{% /choosable %}}


{{% choosable language nodejs %}}
<dl class="resources-properties">

    <dt class="property-optional"
            title="Optional">
        <span>runner</span>
        <span class="property-indicator"></span>
        <span class="property-type"><a href="#elastigroupintegrationgitlabrunner">Elastigroup<wbr>Integration<wbr>Gitlab<wbr>Runner?</a></span>
    </dt>
    <dd>{{% md %}}{{% /md %}}</dd>

</dl>
{{% /choosable %}}


{{% choosable language python %}}
<dl class="resources-properties">

    <dt class="property-optional"
            title="Optional">
        <span>runner</span>
        <span class="property-indicator"></span>
        <span class="property-type"><a href="#elastigroupintegrationgitlabrunner">Dict[Elastigroup<wbr>Integration<wbr>Gitlab<wbr>Runner]</a></span>
    </dt>
    <dd>{{% md %}}{{% /md %}}</dd>

</dl>
{{% /choosable %}}





<h4>Elastigroup<wbr>Integration<wbr>Gitlab<wbr>Runner</h4>
{{% choosable language nodejs %}}
> See the <a href="/docs/reference/pkg/nodejs/pulumi/spotinst/types/input/#ElastigroupIntegrationGitlabRunner">input</a> and <a href="/docs/reference/pkg/nodejs/pulumi/spotinst/types/output/#ElastigroupIntegrationGitlabRunner">output</a> API doc for this type.
{{% /choosable %}}

{{% choosable language go %}}
> See the <a href="https://pkg.go.dev/github.com/pulumi/pulumi-spotinst/sdk/go/spotinst/aws?tab=doc#ElastigroupIntegrationGitlabRunnerArgs">input</a> and <a href="https://pkg.go.dev/github.com/pulumi/pulumi-spotinst/sdk/go/spotinst/aws?tab=doc#ElastigroupIntegrationGitlabRunnerOutput">output</a> API doc for this type.
{{% /choosable %}}




{{% choosable language csharp %}}
<dl class="resources-properties">

    <dt class="property-optional"
            title="Optional">
        <span>Is<wbr>Enabled</span>
        <span class="property-indicator"></span>
        <span class="property-type">bool?</span>
    </dt>
    <dd>{{% md %}}{{% /md %}}</dd>

</dl>
{{% /choosable %}}


{{% choosable language go %}}
<dl class="resources-properties">

    <dt class="property-optional"
            title="Optional">
        <span>Is<wbr>Enabled</span>
        <span class="property-indicator"></span>
        <span class="property-type">*bool</span>
    </dt>
    <dd>{{% md %}}{{% /md %}}</dd>

</dl>
{{% /choosable %}}


{{% choosable language nodejs %}}
<dl class="resources-properties">

    <dt class="property-optional"
            title="Optional">
        <span>is<wbr>Enabled</span>
        <span class="property-indicator"></span>
        <span class="property-type">boolean?</span>
    </dt>
    <dd>{{% md %}}{{% /md %}}</dd>

</dl>
{{% /choosable %}}


{{% choosable language python %}}
<dl class="resources-properties">

    <dt class="property-optional"
            title="Optional">
        <span>is<wbr>Enabled</span>
        <span class="property-indicator"></span>
        <span class="property-type">bool</span>
    </dt>
    <dd>{{% md %}}{{% /md %}}</dd>

</dl>
{{% /choosable %}}





<h4>Elastigroup<wbr>Integration<wbr>Kubernetes</h4>
{{% choosable language nodejs %}}
> See the <a href="/docs/reference/pkg/nodejs/pulumi/spotinst/types/input/#ElastigroupIntegrationKubernetes">input</a> and <a href="/docs/reference/pkg/nodejs/pulumi/spotinst/types/output/#ElastigroupIntegrationKubernetes">output</a> API doc for this type.
{{% /choosable %}}

{{% choosable language go %}}
> See the <a href="https://pkg.go.dev/github.com/pulumi/pulumi-spotinst/sdk/go/spotinst/aws?tab=doc#ElastigroupIntegrationKubernetesArgs">input</a> and <a href="https://pkg.go.dev/github.com/pulumi/pulumi-spotinst/sdk/go/spotinst/aws?tab=doc#ElastigroupIntegrationKubernetesOutput">output</a> API doc for this type.
{{% /choosable %}}




{{% choosable language csharp %}}
<dl class="resources-properties">

    <dt class="property-optional"
            title="Optional">
        <span>Api<wbr>Server</span>
        <span class="property-indicator"></span>
        <span class="property-type">string?</span>
    </dt>
    <dd>{{% md %}}{{% /md %}}</dd>

    <dt class="property-optional"
            title="Optional">
        <span>Autoscale<wbr>Cooldown</span>
        <span class="property-indicator"></span>
        <span class="property-type">int?</span>
    </dt>
    <dd>{{% md %}}{{% /md %}}</dd>

    <dt class="property-optional"
            title="Optional">
        <span>Autoscale<wbr>Down</span>
        <span class="property-indicator"></span>
        <span class="property-type"><a href="#elastigroupintegrationkubernetesautoscaledown">Elastigroup<wbr>Integration<wbr>Kubernetes<wbr>Autoscale<wbr>Down<wbr>Args?</a></span>
    </dt>
    <dd>{{% md %}}{{% /md %}}</dd>

    <dt class="property-optional"
            title="Optional">
        <span>Autoscale<wbr>Headroom</span>
        <span class="property-indicator"></span>
        <span class="property-type"><a href="#elastigroupintegrationkubernetesautoscaleheadroom">Elastigroup<wbr>Integration<wbr>Kubernetes<wbr>Autoscale<wbr>Headroom<wbr>Args?</a></span>
    </dt>
    <dd>{{% md %}}{{% /md %}}</dd>

    <dt class="property-optional"
            title="Optional">
        <span>Autoscale<wbr>Is<wbr>Auto<wbr>Config</span>
        <span class="property-indicator"></span>
        <span class="property-type">bool?</span>
    </dt>
    <dd>{{% md %}}{{% /md %}}</dd>

    <dt class="property-optional"
            title="Optional">
        <span>Autoscale<wbr>Is<wbr>Enabled</span>
        <span class="property-indicator"></span>
        <span class="property-type">bool?</span>
    </dt>
    <dd>{{% md %}}{{% /md %}}</dd>

    <dt class="property-optional"
            title="Optional">
        <span>Autoscale<wbr>Labels</span>
        <span class="property-indicator"></span>
        <span class="property-type"><a href="#elastigroupintegrationkubernetesautoscalelabel">List&lt;Elastigroup<wbr>Integration<wbr>Kubernetes<wbr>Autoscale<wbr>Label<wbr>Args&gt;?</a></span>
    </dt>
    <dd>{{% md %}}{{% /md %}}</dd>

    <dt class="property-optional"
            title="Optional">
        <span>Cluster<wbr>Identifier</span>
        <span class="property-indicator"></span>
        <span class="property-type">string?</span>
    </dt>
    <dd>{{% md %}}{{% /md %}}</dd>

    <dt class="property-optional"
            title="Optional">
        <span>Integration<wbr>Mode</span>
        <span class="property-indicator"></span>
        <span class="property-type">string?</span>
    </dt>
    <dd>{{% md %}}{{% /md %}}</dd>

    <dt class="property-optional"
            title="Optional">
        <span>Token</span>
        <span class="property-indicator"></span>
        <span class="property-type">string?</span>
    </dt>
    <dd>{{% md %}}{{% /md %}}</dd>

</dl>
{{% /choosable %}}


{{% choosable language go %}}
<dl class="resources-properties">

    <dt class="property-optional"
            title="Optional">
        <span>Api<wbr>Server</span>
        <span class="property-indicator"></span>
        <span class="property-type">*string</span>
    </dt>
    <dd>{{% md %}}{{% /md %}}</dd>

    <dt class="property-optional"
            title="Optional">
        <span>Autoscale<wbr>Cooldown</span>
        <span class="property-indicator"></span>
        <span class="property-type">*int</span>
    </dt>
    <dd>{{% md %}}{{% /md %}}</dd>

    <dt class="property-optional"
            title="Optional">
        <span>Autoscale<wbr>Down</span>
        <span class="property-indicator"></span>
        <span class="property-type"><a href="#elastigroupintegrationkubernetesautoscaledown">*Elastigroup<wbr>Integration<wbr>Kubernetes<wbr>Autoscale<wbr>Down</a></span>
    </dt>
    <dd>{{% md %}}{{% /md %}}</dd>

    <dt class="property-optional"
            title="Optional">
        <span>Autoscale<wbr>Headroom</span>
        <span class="property-indicator"></span>
        <span class="property-type"><a href="#elastigroupintegrationkubernetesautoscaleheadroom">*Elastigroup<wbr>Integration<wbr>Kubernetes<wbr>Autoscale<wbr>Headroom</a></span>
    </dt>
    <dd>{{% md %}}{{% /md %}}</dd>

    <dt class="property-optional"
            title="Optional">
        <span>Autoscale<wbr>Is<wbr>Auto<wbr>Config</span>
        <span class="property-indicator"></span>
        <span class="property-type">*bool</span>
    </dt>
    <dd>{{% md %}}{{% /md %}}</dd>

    <dt class="property-optional"
            title="Optional">
        <span>Autoscale<wbr>Is<wbr>Enabled</span>
        <span class="property-indicator"></span>
        <span class="property-type">*bool</span>
    </dt>
    <dd>{{% md %}}{{% /md %}}</dd>

    <dt class="property-optional"
            title="Optional">
        <span>Autoscale<wbr>Labels</span>
        <span class="property-indicator"></span>
        <span class="property-type"><a href="#elastigroupintegrationkubernetesautoscalelabel">[]Elastigroup<wbr>Integration<wbr>Kubernetes<wbr>Autoscale<wbr>Label</a></span>
    </dt>
    <dd>{{% md %}}{{% /md %}}</dd>

    <dt class="property-optional"
            title="Optional">
        <span>Cluster<wbr>Identifier</span>
        <span class="property-indicator"></span>
        <span class="property-type">*string</span>
    </dt>
    <dd>{{% md %}}{{% /md %}}</dd>

    <dt class="property-optional"
            title="Optional">
        <span>Integration<wbr>Mode</span>
        <span class="property-indicator"></span>
        <span class="property-type">*string</span>
    </dt>
    <dd>{{% md %}}{{% /md %}}</dd>

    <dt class="property-optional"
            title="Optional">
        <span>Token</span>
        <span class="property-indicator"></span>
        <span class="property-type">*string</span>
    </dt>
    <dd>{{% md %}}{{% /md %}}</dd>

</dl>
{{% /choosable %}}


{{% choosable language nodejs %}}
<dl class="resources-properties">

    <dt class="property-optional"
            title="Optional">
        <span>api<wbr>Server</span>
        <span class="property-indicator"></span>
        <span class="property-type">string?</span>
    </dt>
    <dd>{{% md %}}{{% /md %}}</dd>

    <dt class="property-optional"
            title="Optional">
        <span>autoscale<wbr>Cooldown</span>
        <span class="property-indicator"></span>
        <span class="property-type">number?</span>
    </dt>
    <dd>{{% md %}}{{% /md %}}</dd>

    <dt class="property-optional"
            title="Optional">
        <span>autoscale<wbr>Down</span>
        <span class="property-indicator"></span>
        <span class="property-type"><a href="#elastigroupintegrationkubernetesautoscaledown">Elastigroup<wbr>Integration<wbr>Kubernetes<wbr>Autoscale<wbr>Down?</a></span>
    </dt>
    <dd>{{% md %}}{{% /md %}}</dd>

    <dt class="property-optional"
            title="Optional">
        <span>autoscale<wbr>Headroom</span>
        <span class="property-indicator"></span>
        <span class="property-type"><a href="#elastigroupintegrationkubernetesautoscaleheadroom">Elastigroup<wbr>Integration<wbr>Kubernetes<wbr>Autoscale<wbr>Headroom?</a></span>
    </dt>
    <dd>{{% md %}}{{% /md %}}</dd>

    <dt class="property-optional"
            title="Optional">
        <span>autoscale<wbr>Is<wbr>Auto<wbr>Config</span>
        <span class="property-indicator"></span>
        <span class="property-type">boolean?</span>
    </dt>
    <dd>{{% md %}}{{% /md %}}</dd>

    <dt class="property-optional"
            title="Optional">
        <span>autoscale<wbr>Is<wbr>Enabled</span>
        <span class="property-indicator"></span>
        <span class="property-type">boolean?</span>
    </dt>
    <dd>{{% md %}}{{% /md %}}</dd>

    <dt class="property-optional"
            title="Optional">
        <span>autoscale<wbr>Labels</span>
        <span class="property-indicator"></span>
        <span class="property-type"><a href="#elastigroupintegrationkubernetesautoscalelabel">Elastigroup<wbr>Integration<wbr>Kubernetes<wbr>Autoscale<wbr>Label[]?</a></span>
    </dt>
    <dd>{{% md %}}{{% /md %}}</dd>

    <dt class="property-optional"
            title="Optional">
        <span>cluster<wbr>Identifier</span>
        <span class="property-indicator"></span>
        <span class="property-type">string?</span>
    </dt>
    <dd>{{% md %}}{{% /md %}}</dd>

    <dt class="property-optional"
            title="Optional">
        <span>integration<wbr>Mode</span>
        <span class="property-indicator"></span>
        <span class="property-type">string?</span>
    </dt>
    <dd>{{% md %}}{{% /md %}}</dd>

    <dt class="property-optional"
            title="Optional">
        <span>token</span>
        <span class="property-indicator"></span>
        <span class="property-type">string?</span>
    </dt>
    <dd>{{% md %}}{{% /md %}}</dd>

</dl>
{{% /choosable %}}


{{% choosable language python %}}
<dl class="resources-properties">

    <dt class="property-optional"
            title="Optional">
        <span>api<wbr>Server</span>
        <span class="property-indicator"></span>
        <span class="property-type">str</span>
    </dt>
    <dd>{{% md %}}{{% /md %}}</dd>

    <dt class="property-optional"
            title="Optional">
        <span>autoscale<wbr>Cooldown</span>
        <span class="property-indicator"></span>
        <span class="property-type">float</span>
    </dt>
    <dd>{{% md %}}{{% /md %}}</dd>

    <dt class="property-optional"
            title="Optional">
        <span>autoscale<wbr>Down</span>
        <span class="property-indicator"></span>
        <span class="property-type"><a href="#elastigroupintegrationkubernetesautoscaledown">Dict[Elastigroup<wbr>Integration<wbr>Kubernetes<wbr>Autoscale<wbr>Down]</a></span>
    </dt>
    <dd>{{% md %}}{{% /md %}}</dd>

    <dt class="property-optional"
            title="Optional">
        <span>autoscale<wbr>Headroom</span>
        <span class="property-indicator"></span>
        <span class="property-type"><a href="#elastigroupintegrationkubernetesautoscaleheadroom">Dict[Elastigroup<wbr>Integration<wbr>Kubernetes<wbr>Autoscale<wbr>Headroom]</a></span>
    </dt>
    <dd>{{% md %}}{{% /md %}}</dd>

    <dt class="property-optional"
            title="Optional">
        <span>autoscale<wbr>Is<wbr>Auto<wbr>Config</span>
        <span class="property-indicator"></span>
        <span class="property-type">bool</span>
    </dt>
    <dd>{{% md %}}{{% /md %}}</dd>

    <dt class="property-optional"
            title="Optional">
        <span>autoscale<wbr>Is<wbr>Enabled</span>
        <span class="property-indicator"></span>
        <span class="property-type">bool</span>
    </dt>
    <dd>{{% md %}}{{% /md %}}</dd>

    <dt class="property-optional"
            title="Optional">
        <span>autoscale<wbr>Labels</span>
        <span class="property-indicator"></span>
        <span class="property-type"><a href="#elastigroupintegrationkubernetesautoscalelabel">List[Elastigroup<wbr>Integration<wbr>Kubernetes<wbr>Autoscale<wbr>Label]</a></span>
    </dt>
    <dd>{{% md %}}{{% /md %}}</dd>

    <dt class="property-optional"
            title="Optional">
        <span>cluster<wbr>Identifier</span>
        <span class="property-indicator"></span>
        <span class="property-type">str</span>
    </dt>
    <dd>{{% md %}}{{% /md %}}</dd>

    <dt class="property-optional"
            title="Optional">
        <span>integration<wbr>Mode</span>
        <span class="property-indicator"></span>
        <span class="property-type">str</span>
    </dt>
    <dd>{{% md %}}{{% /md %}}</dd>

    <dt class="property-optional"
            title="Optional">
        <span>token</span>
        <span class="property-indicator"></span>
        <span class="property-type">str</span>
    </dt>
    <dd>{{% md %}}{{% /md %}}</dd>

</dl>
{{% /choosable %}}





<h4>Elastigroup<wbr>Integration<wbr>Kubernetes<wbr>Autoscale<wbr>Down</h4>
{{% choosable language nodejs %}}
> See the <a href="/docs/reference/pkg/nodejs/pulumi/spotinst/types/input/#ElastigroupIntegrationKubernetesAutoscaleDown">input</a> and <a href="/docs/reference/pkg/nodejs/pulumi/spotinst/types/output/#ElastigroupIntegrationKubernetesAutoscaleDown">output</a> API doc for this type.
{{% /choosable %}}

{{% choosable language go %}}
> See the <a href="https://pkg.go.dev/github.com/pulumi/pulumi-spotinst/sdk/go/spotinst/aws?tab=doc#ElastigroupIntegrationKubernetesAutoscaleDownArgs">input</a> and <a href="https://pkg.go.dev/github.com/pulumi/pulumi-spotinst/sdk/go/spotinst/aws?tab=doc#ElastigroupIntegrationKubernetesAutoscaleDownOutput">output</a> API doc for this type.
{{% /choosable %}}




{{% choosable language csharp %}}
<dl class="resources-properties">

    <dt class="property-optional"
            title="Optional">
        <span>Evaluation<wbr>Periods</span>
        <span class="property-indicator"></span>
        <span class="property-type">int?</span>
    </dt>
    <dd>{{% md %}}{{% /md %}}</dd>

</dl>
{{% /choosable %}}


{{% choosable language go %}}
<dl class="resources-properties">

    <dt class="property-optional"
            title="Optional">
        <span>Evaluation<wbr>Periods</span>
        <span class="property-indicator"></span>
        <span class="property-type">*int</span>
    </dt>
    <dd>{{% md %}}{{% /md %}}</dd>

</dl>
{{% /choosable %}}


{{% choosable language nodejs %}}
<dl class="resources-properties">

    <dt class="property-optional"
            title="Optional">
        <span>evaluation<wbr>Periods</span>
        <span class="property-indicator"></span>
        <span class="property-type">number?</span>
    </dt>
    <dd>{{% md %}}{{% /md %}}</dd>

</dl>
{{% /choosable %}}


{{% choosable language python %}}
<dl class="resources-properties">

    <dt class="property-optional"
            title="Optional">
        <span>evaluation<wbr>Periods</span>
        <span class="property-indicator"></span>
        <span class="property-type">float</span>
    </dt>
    <dd>{{% md %}}{{% /md %}}</dd>

</dl>
{{% /choosable %}}





<h4>Elastigroup<wbr>Integration<wbr>Kubernetes<wbr>Autoscale<wbr>Headroom</h4>
{{% choosable language nodejs %}}
> See the <a href="/docs/reference/pkg/nodejs/pulumi/spotinst/types/input/#ElastigroupIntegrationKubernetesAutoscaleHeadroom">input</a> and <a href="/docs/reference/pkg/nodejs/pulumi/spotinst/types/output/#ElastigroupIntegrationKubernetesAutoscaleHeadroom">output</a> API doc for this type.
{{% /choosable %}}

{{% choosable language go %}}
> See the <a href="https://pkg.go.dev/github.com/pulumi/pulumi-spotinst/sdk/go/spotinst/aws?tab=doc#ElastigroupIntegrationKubernetesAutoscaleHeadroomArgs">input</a> and <a href="https://pkg.go.dev/github.com/pulumi/pulumi-spotinst/sdk/go/spotinst/aws?tab=doc#ElastigroupIntegrationKubernetesAutoscaleHeadroomOutput">output</a> API doc for this type.
{{% /choosable %}}




{{% choosable language csharp %}}
<dl class="resources-properties">

    <dt class="property-optional"
            title="Optional">
        <span>Cpu<wbr>Per<wbr>Unit</span>
        <span class="property-indicator"></span>
        <span class="property-type">int?</span>
    </dt>
    <dd>{{% md %}}{{% /md %}}</dd>

    <dt class="property-optional"
            title="Optional">
        <span>Memory<wbr>Per<wbr>Unit</span>
        <span class="property-indicator"></span>
        <span class="property-type">int?</span>
    </dt>
    <dd>{{% md %}}{{% /md %}}</dd>

    <dt class="property-optional"
            title="Optional">
        <span>Num<wbr>Of<wbr>Units</span>
        <span class="property-indicator"></span>
        <span class="property-type">int?</span>
    </dt>
    <dd>{{% md %}}{{% /md %}}</dd>

</dl>
{{% /choosable %}}


{{% choosable language go %}}
<dl class="resources-properties">

    <dt class="property-optional"
            title="Optional">
        <span>Cpu<wbr>Per<wbr>Unit</span>
        <span class="property-indicator"></span>
        <span class="property-type">*int</span>
    </dt>
    <dd>{{% md %}}{{% /md %}}</dd>

    <dt class="property-optional"
            title="Optional">
        <span>Memory<wbr>Per<wbr>Unit</span>
        <span class="property-indicator"></span>
        <span class="property-type">*int</span>
    </dt>
    <dd>{{% md %}}{{% /md %}}</dd>

    <dt class="property-optional"
            title="Optional">
        <span>Num<wbr>Of<wbr>Units</span>
        <span class="property-indicator"></span>
        <span class="property-type">*int</span>
    </dt>
    <dd>{{% md %}}{{% /md %}}</dd>

</dl>
{{% /choosable %}}


{{% choosable language nodejs %}}
<dl class="resources-properties">

    <dt class="property-optional"
            title="Optional">
        <span>cpu<wbr>Per<wbr>Unit</span>
        <span class="property-indicator"></span>
        <span class="property-type">number?</span>
    </dt>
    <dd>{{% md %}}{{% /md %}}</dd>

    <dt class="property-optional"
            title="Optional">
        <span>memory<wbr>Per<wbr>Unit</span>
        <span class="property-indicator"></span>
        <span class="property-type">number?</span>
    </dt>
    <dd>{{% md %}}{{% /md %}}</dd>

    <dt class="property-optional"
            title="Optional">
        <span>num<wbr>Of<wbr>Units</span>
        <span class="property-indicator"></span>
        <span class="property-type">number?</span>
    </dt>
    <dd>{{% md %}}{{% /md %}}</dd>

</dl>
{{% /choosable %}}


{{% choosable language python %}}
<dl class="resources-properties">

    <dt class="property-optional"
            title="Optional">
        <span>cpu<wbr>Per<wbr>Unit</span>
        <span class="property-indicator"></span>
        <span class="property-type">float</span>
    </dt>
    <dd>{{% md %}}{{% /md %}}</dd>

    <dt class="property-optional"
            title="Optional">
        <span>memory<wbr>Per<wbr>Unit</span>
        <span class="property-indicator"></span>
        <span class="property-type">float</span>
    </dt>
    <dd>{{% md %}}{{% /md %}}</dd>

    <dt class="property-optional"
            title="Optional">
        <span>num<wbr>Of<wbr>Units</span>
        <span class="property-indicator"></span>
        <span class="property-type">float</span>
    </dt>
    <dd>{{% md %}}{{% /md %}}</dd>

</dl>
{{% /choosable %}}





<h4>Elastigroup<wbr>Integration<wbr>Kubernetes<wbr>Autoscale<wbr>Label</h4>
{{% choosable language nodejs %}}
> See the <a href="/docs/reference/pkg/nodejs/pulumi/spotinst/types/input/#ElastigroupIntegrationKubernetesAutoscaleLabel">input</a> and <a href="/docs/reference/pkg/nodejs/pulumi/spotinst/types/output/#ElastigroupIntegrationKubernetesAutoscaleLabel">output</a> API doc for this type.
{{% /choosable %}}

{{% choosable language go %}}
> See the <a href="https://pkg.go.dev/github.com/pulumi/pulumi-spotinst/sdk/go/spotinst/aws?tab=doc#ElastigroupIntegrationKubernetesAutoscaleLabelArgs">input</a> and <a href="https://pkg.go.dev/github.com/pulumi/pulumi-spotinst/sdk/go/spotinst/aws?tab=doc#ElastigroupIntegrationKubernetesAutoscaleLabelOutput">output</a> API doc for this type.
{{% /choosable %}}




{{% choosable language csharp %}}
<dl class="resources-properties">

    <dt class="property-required"
            title="Required">
        <span>Key</span>
        <span class="property-indicator"></span>
        <span class="property-type">string</span>
    </dt>
    <dd>{{% md %}}{{% /md %}}</dd>

    <dt class="property-required"
            title="Required">
        <span>Value</span>
        <span class="property-indicator"></span>
        <span class="property-type">string</span>
    </dt>
    <dd>{{% md %}}{{% /md %}}</dd>

</dl>
{{% /choosable %}}


{{% choosable language go %}}
<dl class="resources-properties">

    <dt class="property-required"
            title="Required">
        <span>Key</span>
        <span class="property-indicator"></span>
        <span class="property-type">string</span>
    </dt>
    <dd>{{% md %}}{{% /md %}}</dd>

    <dt class="property-required"
            title="Required">
        <span>Value</span>
        <span class="property-indicator"></span>
        <span class="property-type">string</span>
    </dt>
    <dd>{{% md %}}{{% /md %}}</dd>

</dl>
{{% /choosable %}}


{{% choosable language nodejs %}}
<dl class="resources-properties">

    <dt class="property-required"
            title="Required">
        <span>key</span>
        <span class="property-indicator"></span>
        <span class="property-type">string</span>
    </dt>
    <dd>{{% md %}}{{% /md %}}</dd>

    <dt class="property-required"
            title="Required">
        <span>value</span>
        <span class="property-indicator"></span>
        <span class="property-type">string</span>
    </dt>
    <dd>{{% md %}}{{% /md %}}</dd>

</dl>
{{% /choosable %}}


{{% choosable language python %}}
<dl class="resources-properties">

    <dt class="property-required"
            title="Required">
        <span>key</span>
        <span class="property-indicator"></span>
        <span class="property-type">str</span>
    </dt>
    <dd>{{% md %}}{{% /md %}}</dd>

    <dt class="property-required"
            title="Required">
        <span>value</span>
        <span class="property-indicator"></span>
        <span class="property-type">str</span>
    </dt>
    <dd>{{% md %}}{{% /md %}}</dd>

</dl>
{{% /choosable %}}





<h4>Elastigroup<wbr>Integration<wbr>Mesosphere</h4>
{{% choosable language nodejs %}}
> See the <a href="/docs/reference/pkg/nodejs/pulumi/spotinst/types/input/#ElastigroupIntegrationMesosphere">input</a> and <a href="/docs/reference/pkg/nodejs/pulumi/spotinst/types/output/#ElastigroupIntegrationMesosphere">output</a> API doc for this type.
{{% /choosable %}}

{{% choosable language go %}}
> See the <a href="https://pkg.go.dev/github.com/pulumi/pulumi-spotinst/sdk/go/spotinst/aws?tab=doc#ElastigroupIntegrationMesosphereArgs">input</a> and <a href="https://pkg.go.dev/github.com/pulumi/pulumi-spotinst/sdk/go/spotinst/aws?tab=doc#ElastigroupIntegrationMesosphereOutput">output</a> API doc for this type.
{{% /choosable %}}




{{% choosable language csharp %}}
<dl class="resources-properties">

    <dt class="property-required"
            title="Required">
        <span>Api<wbr>Server</span>
        <span class="property-indicator"></span>
        <span class="property-type">string</span>
    </dt>
    <dd>{{% md %}}{{% /md %}}</dd>

</dl>
{{% /choosable %}}


{{% choosable language go %}}
<dl class="resources-properties">

    <dt class="property-required"
            title="Required">
        <span>Api<wbr>Server</span>
        <span class="property-indicator"></span>
        <span class="property-type">string</span>
    </dt>
    <dd>{{% md %}}{{% /md %}}</dd>

</dl>
{{% /choosable %}}


{{% choosable language nodejs %}}
<dl class="resources-properties">

    <dt class="property-required"
            title="Required">
        <span>api<wbr>Server</span>
        <span class="property-indicator"></span>
        <span class="property-type">string</span>
    </dt>
    <dd>{{% md %}}{{% /md %}}</dd>

</dl>
{{% /choosable %}}


{{% choosable language python %}}
<dl class="resources-properties">

    <dt class="property-required"
            title="Required">
        <span>api<wbr>Server</span>
        <span class="property-indicator"></span>
        <span class="property-type">str</span>
    </dt>
    <dd>{{% md %}}{{% /md %}}</dd>

</dl>
{{% /choosable %}}





<h4>Elastigroup<wbr>Integration<wbr>Multai<wbr>Runtime</h4>
{{% choosable language nodejs %}}
> See the <a href="/docs/reference/pkg/nodejs/pulumi/spotinst/types/input/#ElastigroupIntegrationMultaiRuntime">input</a> and <a href="/docs/reference/pkg/nodejs/pulumi/spotinst/types/output/#ElastigroupIntegrationMultaiRuntime">output</a> API doc for this type.
{{% /choosable %}}

{{% choosable language go %}}
> See the <a href="https://pkg.go.dev/github.com/pulumi/pulumi-spotinst/sdk/go/spotinst/aws?tab=doc#ElastigroupIntegrationMultaiRuntimeArgs">input</a> and <a href="https://pkg.go.dev/github.com/pulumi/pulumi-spotinst/sdk/go/spotinst/aws?tab=doc#ElastigroupIntegrationMultaiRuntimeOutput">output</a> API doc for this type.
{{% /choosable %}}




{{% choosable language csharp %}}
<dl class="resources-properties">

    <dt class="property-required"
            title="Required">
        <span>Deployment<wbr>Id</span>
        <span class="property-indicator"></span>
        <span class="property-type">string</span>
    </dt>
    <dd>{{% md %}}{{% /md %}}</dd>

</dl>
{{% /choosable %}}


{{% choosable language go %}}
<dl class="resources-properties">

    <dt class="property-required"
            title="Required">
        <span>Deployment<wbr>Id</span>
        <span class="property-indicator"></span>
        <span class="property-type">string</span>
    </dt>
    <dd>{{% md %}}{{% /md %}}</dd>

</dl>
{{% /choosable %}}


{{% choosable language nodejs %}}
<dl class="resources-properties">

    <dt class="property-required"
            title="Required">
        <span>deployment<wbr>Id</span>
        <span class="property-indicator"></span>
        <span class="property-type">string</span>
    </dt>
    <dd>{{% md %}}{{% /md %}}</dd>

</dl>
{{% /choosable %}}


{{% choosable language python %}}
<dl class="resources-properties">

    <dt class="property-required"
            title="Required">
        <span>deployment_<wbr>id</span>
        <span class="property-indicator"></span>
        <span class="property-type">str</span>
    </dt>
    <dd>{{% md %}}{{% /md %}}</dd>

</dl>
{{% /choosable %}}





<h4>Elastigroup<wbr>Integration<wbr>Nomad</h4>
{{% choosable language nodejs %}}
> See the <a href="/docs/reference/pkg/nodejs/pulumi/spotinst/types/input/#ElastigroupIntegrationNomad">input</a> and <a href="/docs/reference/pkg/nodejs/pulumi/spotinst/types/output/#ElastigroupIntegrationNomad">output</a> API doc for this type.
{{% /choosable %}}

{{% choosable language go %}}
> See the <a href="https://pkg.go.dev/github.com/pulumi/pulumi-spotinst/sdk/go/spotinst/aws?tab=doc#ElastigroupIntegrationNomadArgs">input</a> and <a href="https://pkg.go.dev/github.com/pulumi/pulumi-spotinst/sdk/go/spotinst/aws?tab=doc#ElastigroupIntegrationNomadOutput">output</a> API doc for this type.
{{% /choosable %}}




{{% choosable language csharp %}}
<dl class="resources-properties">

    <dt class="property-optional"
            title="Optional">
        <span>Acl<wbr>Token</span>
        <span class="property-indicator"></span>
        <span class="property-type">string?</span>
    </dt>
    <dd>{{% md %}}{{% /md %}}</dd>

    <dt class="property-optional"
            title="Optional">
        <span>Autoscale<wbr>Constraints</span>
        <span class="property-indicator"></span>
        <span class="property-type"><a href="#elastigroupintegrationnomadautoscaleconstraint">List&lt;Elastigroup<wbr>Integration<wbr>Nomad<wbr>Autoscale<wbr>Constraint<wbr>Args&gt;?</a></span>
    </dt>
    <dd>{{% md %}}{{% /md %}}</dd>

    <dt class="property-optional"
            title="Optional">
        <span>Autoscale<wbr>Cooldown</span>
        <span class="property-indicator"></span>
        <span class="property-type">int?</span>
    </dt>
    <dd>{{% md %}}{{% /md %}}</dd>

    <dt class="property-optional"
            title="Optional">
        <span>Autoscale<wbr>Down</span>
        <span class="property-indicator"></span>
        <span class="property-type"><a href="#elastigroupintegrationnomadautoscaledown">Elastigroup<wbr>Integration<wbr>Nomad<wbr>Autoscale<wbr>Down<wbr>Args?</a></span>
    </dt>
    <dd>{{% md %}}{{% /md %}}</dd>

    <dt class="property-optional"
            title="Optional">
        <span>Autoscale<wbr>Headroom</span>
        <span class="property-indicator"></span>
        <span class="property-type"><a href="#elastigroupintegrationnomadautoscaleheadroom">Elastigroup<wbr>Integration<wbr>Nomad<wbr>Autoscale<wbr>Headroom<wbr>Args?</a></span>
    </dt>
    <dd>{{% md %}}{{% /md %}}</dd>

    <dt class="property-optional"
            title="Optional">
        <span>Autoscale<wbr>Is<wbr>Enabled</span>
        <span class="property-indicator"></span>
        <span class="property-type">bool?</span>
    </dt>
    <dd>{{% md %}}{{% /md %}}</dd>

    <dt class="property-required"
            title="Required">
        <span>Master<wbr>Host</span>
        <span class="property-indicator"></span>
        <span class="property-type">string</span>
    </dt>
    <dd>{{% md %}}{{% /md %}}</dd>

    <dt class="property-required"
            title="Required">
        <span>Master<wbr>Port</span>
        <span class="property-indicator"></span>
        <span class="property-type">int</span>
    </dt>
    <dd>{{% md %}}{{% /md %}}</dd>

</dl>
{{% /choosable %}}


{{% choosable language go %}}
<dl class="resources-properties">

    <dt class="property-optional"
            title="Optional">
        <span>Acl<wbr>Token</span>
        <span class="property-indicator"></span>
        <span class="property-type">*string</span>
    </dt>
    <dd>{{% md %}}{{% /md %}}</dd>

    <dt class="property-optional"
            title="Optional">
        <span>Autoscale<wbr>Constraints</span>
        <span class="property-indicator"></span>
        <span class="property-type"><a href="#elastigroupintegrationnomadautoscaleconstraint">[]Elastigroup<wbr>Integration<wbr>Nomad<wbr>Autoscale<wbr>Constraint</a></span>
    </dt>
    <dd>{{% md %}}{{% /md %}}</dd>

    <dt class="property-optional"
            title="Optional">
        <span>Autoscale<wbr>Cooldown</span>
        <span class="property-indicator"></span>
        <span class="property-type">*int</span>
    </dt>
    <dd>{{% md %}}{{% /md %}}</dd>

    <dt class="property-optional"
            title="Optional">
        <span>Autoscale<wbr>Down</span>
        <span class="property-indicator"></span>
        <span class="property-type"><a href="#elastigroupintegrationnomadautoscaledown">*Elastigroup<wbr>Integration<wbr>Nomad<wbr>Autoscale<wbr>Down</a></span>
    </dt>
    <dd>{{% md %}}{{% /md %}}</dd>

    <dt class="property-optional"
            title="Optional">
        <span>Autoscale<wbr>Headroom</span>
        <span class="property-indicator"></span>
        <span class="property-type"><a href="#elastigroupintegrationnomadautoscaleheadroom">*Elastigroup<wbr>Integration<wbr>Nomad<wbr>Autoscale<wbr>Headroom</a></span>
    </dt>
    <dd>{{% md %}}{{% /md %}}</dd>

    <dt class="property-optional"
            title="Optional">
        <span>Autoscale<wbr>Is<wbr>Enabled</span>
        <span class="property-indicator"></span>
        <span class="property-type">*bool</span>
    </dt>
    <dd>{{% md %}}{{% /md %}}</dd>

    <dt class="property-required"
            title="Required">
        <span>Master<wbr>Host</span>
        <span class="property-indicator"></span>
        <span class="property-type">string</span>
    </dt>
    <dd>{{% md %}}{{% /md %}}</dd>

    <dt class="property-required"
            title="Required">
        <span>Master<wbr>Port</span>
        <span class="property-indicator"></span>
        <span class="property-type">int</span>
    </dt>
    <dd>{{% md %}}{{% /md %}}</dd>

</dl>
{{% /choosable %}}


{{% choosable language nodejs %}}
<dl class="resources-properties">

    <dt class="property-optional"
            title="Optional">
        <span>acl<wbr>Token</span>
        <span class="property-indicator"></span>
        <span class="property-type">string?</span>
    </dt>
    <dd>{{% md %}}{{% /md %}}</dd>

    <dt class="property-optional"
            title="Optional">
        <span>autoscale<wbr>Constraints</span>
        <span class="property-indicator"></span>
        <span class="property-type"><a href="#elastigroupintegrationnomadautoscaleconstraint">Elastigroup<wbr>Integration<wbr>Nomad<wbr>Autoscale<wbr>Constraint[]?</a></span>
    </dt>
    <dd>{{% md %}}{{% /md %}}</dd>

    <dt class="property-optional"
            title="Optional">
        <span>autoscale<wbr>Cooldown</span>
        <span class="property-indicator"></span>
        <span class="property-type">number?</span>
    </dt>
    <dd>{{% md %}}{{% /md %}}</dd>

    <dt class="property-optional"
            title="Optional">
        <span>autoscale<wbr>Down</span>
        <span class="property-indicator"></span>
        <span class="property-type"><a href="#elastigroupintegrationnomadautoscaledown">Elastigroup<wbr>Integration<wbr>Nomad<wbr>Autoscale<wbr>Down?</a></span>
    </dt>
    <dd>{{% md %}}{{% /md %}}</dd>

    <dt class="property-optional"
            title="Optional">
        <span>autoscale<wbr>Headroom</span>
        <span class="property-indicator"></span>
        <span class="property-type"><a href="#elastigroupintegrationnomadautoscaleheadroom">Elastigroup<wbr>Integration<wbr>Nomad<wbr>Autoscale<wbr>Headroom?</a></span>
    </dt>
    <dd>{{% md %}}{{% /md %}}</dd>

    <dt class="property-optional"
            title="Optional">
        <span>autoscale<wbr>Is<wbr>Enabled</span>
        <span class="property-indicator"></span>
        <span class="property-type">boolean?</span>
    </dt>
    <dd>{{% md %}}{{% /md %}}</dd>

    <dt class="property-required"
            title="Required">
        <span>master<wbr>Host</span>
        <span class="property-indicator"></span>
        <span class="property-type">string</span>
    </dt>
    <dd>{{% md %}}{{% /md %}}</dd>

    <dt class="property-required"
            title="Required">
        <span>master<wbr>Port</span>
        <span class="property-indicator"></span>
        <span class="property-type">number</span>
    </dt>
    <dd>{{% md %}}{{% /md %}}</dd>

</dl>
{{% /choosable %}}


{{% choosable language python %}}
<dl class="resources-properties">

    <dt class="property-optional"
            title="Optional">
        <span>acl<wbr>Token</span>
        <span class="property-indicator"></span>
        <span class="property-type">str</span>
    </dt>
    <dd>{{% md %}}{{% /md %}}</dd>

    <dt class="property-optional"
            title="Optional">
        <span>autoscale<wbr>Constraints</span>
        <span class="property-indicator"></span>
        <span class="property-type"><a href="#elastigroupintegrationnomadautoscaleconstraint">List[Elastigroup<wbr>Integration<wbr>Nomad<wbr>Autoscale<wbr>Constraint]</a></span>
    </dt>
    <dd>{{% md %}}{{% /md %}}</dd>

    <dt class="property-optional"
            title="Optional">
        <span>autoscale<wbr>Cooldown</span>
        <span class="property-indicator"></span>
        <span class="property-type">float</span>
    </dt>
    <dd>{{% md %}}{{% /md %}}</dd>

    <dt class="property-optional"
            title="Optional">
        <span>autoscale<wbr>Down</span>
        <span class="property-indicator"></span>
        <span class="property-type"><a href="#elastigroupintegrationnomadautoscaledown">Dict[Elastigroup<wbr>Integration<wbr>Nomad<wbr>Autoscale<wbr>Down]</a></span>
    </dt>
    <dd>{{% md %}}{{% /md %}}</dd>

    <dt class="property-optional"
            title="Optional">
        <span>autoscale<wbr>Headroom</span>
        <span class="property-indicator"></span>
        <span class="property-type"><a href="#elastigroupintegrationnomadautoscaleheadroom">Dict[Elastigroup<wbr>Integration<wbr>Nomad<wbr>Autoscale<wbr>Headroom]</a></span>
    </dt>
    <dd>{{% md %}}{{% /md %}}</dd>

    <dt class="property-optional"
            title="Optional">
        <span>autoscale<wbr>Is<wbr>Enabled</span>
        <span class="property-indicator"></span>
        <span class="property-type">bool</span>
    </dt>
    <dd>{{% md %}}{{% /md %}}</dd>

    <dt class="property-required"
            title="Required">
        <span>master<wbr>Host</span>
        <span class="property-indicator"></span>
        <span class="property-type">str</span>
    </dt>
    <dd>{{% md %}}{{% /md %}}</dd>

    <dt class="property-required"
            title="Required">
        <span>master<wbr>Port</span>
        <span class="property-indicator"></span>
        <span class="property-type">float</span>
    </dt>
    <dd>{{% md %}}{{% /md %}}</dd>

</dl>
{{% /choosable %}}





<h4>Elastigroup<wbr>Integration<wbr>Nomad<wbr>Autoscale<wbr>Constraint</h4>
{{% choosable language nodejs %}}
> See the <a href="/docs/reference/pkg/nodejs/pulumi/spotinst/types/input/#ElastigroupIntegrationNomadAutoscaleConstraint">input</a> and <a href="/docs/reference/pkg/nodejs/pulumi/spotinst/types/output/#ElastigroupIntegrationNomadAutoscaleConstraint">output</a> API doc for this type.
{{% /choosable %}}

{{% choosable language go %}}
> See the <a href="https://pkg.go.dev/github.com/pulumi/pulumi-spotinst/sdk/go/spotinst/aws?tab=doc#ElastigroupIntegrationNomadAutoscaleConstraintArgs">input</a> and <a href="https://pkg.go.dev/github.com/pulumi/pulumi-spotinst/sdk/go/spotinst/aws?tab=doc#ElastigroupIntegrationNomadAutoscaleConstraintOutput">output</a> API doc for this type.
{{% /choosable %}}




{{% choosable language csharp %}}
<dl class="resources-properties">

    <dt class="property-required"
            title="Required">
        <span>Key</span>
        <span class="property-indicator"></span>
        <span class="property-type">string</span>
    </dt>
    <dd>{{% md %}}{{% /md %}}</dd>

    <dt class="property-required"
            title="Required">
        <span>Value</span>
        <span class="property-indicator"></span>
        <span class="property-type">string</span>
    </dt>
    <dd>{{% md %}}{{% /md %}}</dd>

</dl>
{{% /choosable %}}


{{% choosable language go %}}
<dl class="resources-properties">

    <dt class="property-required"
            title="Required">
        <span>Key</span>
        <span class="property-indicator"></span>
        <span class="property-type">string</span>
    </dt>
    <dd>{{% md %}}{{% /md %}}</dd>

    <dt class="property-required"
            title="Required">
        <span>Value</span>
        <span class="property-indicator"></span>
        <span class="property-type">string</span>
    </dt>
    <dd>{{% md %}}{{% /md %}}</dd>

</dl>
{{% /choosable %}}


{{% choosable language nodejs %}}
<dl class="resources-properties">

    <dt class="property-required"
            title="Required">
        <span>key</span>
        <span class="property-indicator"></span>
        <span class="property-type">string</span>
    </dt>
    <dd>{{% md %}}{{% /md %}}</dd>

    <dt class="property-required"
            title="Required">
        <span>value</span>
        <span class="property-indicator"></span>
        <span class="property-type">string</span>
    </dt>
    <dd>{{% md %}}{{% /md %}}</dd>

</dl>
{{% /choosable %}}


{{% choosable language python %}}
<dl class="resources-properties">

    <dt class="property-required"
            title="Required">
        <span>key</span>
        <span class="property-indicator"></span>
        <span class="property-type">str</span>
    </dt>
    <dd>{{% md %}}{{% /md %}}</dd>

    <dt class="property-required"
            title="Required">
        <span>value</span>
        <span class="property-indicator"></span>
        <span class="property-type">str</span>
    </dt>
    <dd>{{% md %}}{{% /md %}}</dd>

</dl>
{{% /choosable %}}





<h4>Elastigroup<wbr>Integration<wbr>Nomad<wbr>Autoscale<wbr>Down</h4>
{{% choosable language nodejs %}}
> See the <a href="/docs/reference/pkg/nodejs/pulumi/spotinst/types/input/#ElastigroupIntegrationNomadAutoscaleDown">input</a> and <a href="/docs/reference/pkg/nodejs/pulumi/spotinst/types/output/#ElastigroupIntegrationNomadAutoscaleDown">output</a> API doc for this type.
{{% /choosable %}}

{{% choosable language go %}}
> See the <a href="https://pkg.go.dev/github.com/pulumi/pulumi-spotinst/sdk/go/spotinst/aws?tab=doc#ElastigroupIntegrationNomadAutoscaleDownArgs">input</a> and <a href="https://pkg.go.dev/github.com/pulumi/pulumi-spotinst/sdk/go/spotinst/aws?tab=doc#ElastigroupIntegrationNomadAutoscaleDownOutput">output</a> API doc for this type.
{{% /choosable %}}




{{% choosable language csharp %}}
<dl class="resources-properties">

    <dt class="property-optional"
            title="Optional">
        <span>Evaluation<wbr>Periods</span>
        <span class="property-indicator"></span>
        <span class="property-type">int?</span>
    </dt>
    <dd>{{% md %}}{{% /md %}}</dd>

</dl>
{{% /choosable %}}


{{% choosable language go %}}
<dl class="resources-properties">

    <dt class="property-optional"
            title="Optional">
        <span>Evaluation<wbr>Periods</span>
        <span class="property-indicator"></span>
        <span class="property-type">*int</span>
    </dt>
    <dd>{{% md %}}{{% /md %}}</dd>

</dl>
{{% /choosable %}}


{{% choosable language nodejs %}}
<dl class="resources-properties">

    <dt class="property-optional"
            title="Optional">
        <span>evaluation<wbr>Periods</span>
        <span class="property-indicator"></span>
        <span class="property-type">number?</span>
    </dt>
    <dd>{{% md %}}{{% /md %}}</dd>

</dl>
{{% /choosable %}}


{{% choosable language python %}}
<dl class="resources-properties">

    <dt class="property-optional"
            title="Optional">
        <span>evaluation<wbr>Periods</span>
        <span class="property-indicator"></span>
        <span class="property-type">float</span>
    </dt>
    <dd>{{% md %}}{{% /md %}}</dd>

</dl>
{{% /choosable %}}





<h4>Elastigroup<wbr>Integration<wbr>Nomad<wbr>Autoscale<wbr>Headroom</h4>
{{% choosable language nodejs %}}
> See the <a href="/docs/reference/pkg/nodejs/pulumi/spotinst/types/input/#ElastigroupIntegrationNomadAutoscaleHeadroom">input</a> and <a href="/docs/reference/pkg/nodejs/pulumi/spotinst/types/output/#ElastigroupIntegrationNomadAutoscaleHeadroom">output</a> API doc for this type.
{{% /choosable %}}

{{% choosable language go %}}
> See the <a href="https://pkg.go.dev/github.com/pulumi/pulumi-spotinst/sdk/go/spotinst/aws?tab=doc#ElastigroupIntegrationNomadAutoscaleHeadroomArgs">input</a> and <a href="https://pkg.go.dev/github.com/pulumi/pulumi-spotinst/sdk/go/spotinst/aws?tab=doc#ElastigroupIntegrationNomadAutoscaleHeadroomOutput">output</a> API doc for this type.
{{% /choosable %}}




{{% choosable language csharp %}}
<dl class="resources-properties">

    <dt class="property-optional"
            title="Optional">
        <span>Cpu<wbr>Per<wbr>Unit</span>
        <span class="property-indicator"></span>
        <span class="property-type">int?</span>
    </dt>
    <dd>{{% md %}}{{% /md %}}</dd>

    <dt class="property-optional"
            title="Optional">
        <span>Memory<wbr>Per<wbr>Unit</span>
        <span class="property-indicator"></span>
        <span class="property-type">int?</span>
    </dt>
    <dd>{{% md %}}{{% /md %}}</dd>

    <dt class="property-optional"
            title="Optional">
        <span>Num<wbr>Of<wbr>Units</span>
        <span class="property-indicator"></span>
        <span class="property-type">int?</span>
    </dt>
    <dd>{{% md %}}{{% /md %}}</dd>

</dl>
{{% /choosable %}}


{{% choosable language go %}}
<dl class="resources-properties">

    <dt class="property-optional"
            title="Optional">
        <span>Cpu<wbr>Per<wbr>Unit</span>
        <span class="property-indicator"></span>
        <span class="property-type">*int</span>
    </dt>
    <dd>{{% md %}}{{% /md %}}</dd>

    <dt class="property-optional"
            title="Optional">
        <span>Memory<wbr>Per<wbr>Unit</span>
        <span class="property-indicator"></span>
        <span class="property-type">*int</span>
    </dt>
    <dd>{{% md %}}{{% /md %}}</dd>

    <dt class="property-optional"
            title="Optional">
        <span>Num<wbr>Of<wbr>Units</span>
        <span class="property-indicator"></span>
        <span class="property-type">*int</span>
    </dt>
    <dd>{{% md %}}{{% /md %}}</dd>

</dl>
{{% /choosable %}}


{{% choosable language nodejs %}}
<dl class="resources-properties">

    <dt class="property-optional"
            title="Optional">
        <span>cpu<wbr>Per<wbr>Unit</span>
        <span class="property-indicator"></span>
        <span class="property-type">number?</span>
    </dt>
    <dd>{{% md %}}{{% /md %}}</dd>

    <dt class="property-optional"
            title="Optional">
        <span>memory<wbr>Per<wbr>Unit</span>
        <span class="property-indicator"></span>
        <span class="property-type">number?</span>
    </dt>
    <dd>{{% md %}}{{% /md %}}</dd>

    <dt class="property-optional"
            title="Optional">
        <span>num<wbr>Of<wbr>Units</span>
        <span class="property-indicator"></span>
        <span class="property-type">number?</span>
    </dt>
    <dd>{{% md %}}{{% /md %}}</dd>

</dl>
{{% /choosable %}}


{{% choosable language python %}}
<dl class="resources-properties">

    <dt class="property-optional"
            title="Optional">
        <span>cpu<wbr>Per<wbr>Unit</span>
        <span class="property-indicator"></span>
        <span class="property-type">float</span>
    </dt>
    <dd>{{% md %}}{{% /md %}}</dd>

    <dt class="property-optional"
            title="Optional">
        <span>memory<wbr>Per<wbr>Unit</span>
        <span class="property-indicator"></span>
        <span class="property-type">float</span>
    </dt>
    <dd>{{% md %}}{{% /md %}}</dd>

    <dt class="property-optional"
            title="Optional">
        <span>num<wbr>Of<wbr>Units</span>
        <span class="property-indicator"></span>
        <span class="property-type">float</span>
    </dt>
    <dd>{{% md %}}{{% /md %}}</dd>

</dl>
{{% /choosable %}}





<h4>Elastigroup<wbr>Integration<wbr>Rancher</h4>
{{% choosable language nodejs %}}
> See the <a href="/docs/reference/pkg/nodejs/pulumi/spotinst/types/input/#ElastigroupIntegrationRancher">input</a> and <a href="/docs/reference/pkg/nodejs/pulumi/spotinst/types/output/#ElastigroupIntegrationRancher">output</a> API doc for this type.
{{% /choosable %}}

{{% choosable language go %}}
> See the <a href="https://pkg.go.dev/github.com/pulumi/pulumi-spotinst/sdk/go/spotinst/aws?tab=doc#ElastigroupIntegrationRancherArgs">input</a> and <a href="https://pkg.go.dev/github.com/pulumi/pulumi-spotinst/sdk/go/spotinst/aws?tab=doc#ElastigroupIntegrationRancherOutput">output</a> API doc for this type.
{{% /choosable %}}




{{% choosable language csharp %}}
<dl class="resources-properties">

    <dt class="property-required"
            title="Required">
        <span>Access<wbr>Key</span>
        <span class="property-indicator"></span>
        <span class="property-type">string</span>
    </dt>
    <dd>{{% md %}}{{% /md %}}</dd>

    <dt class="property-required"
            title="Required">
        <span>Master<wbr>Host</span>
        <span class="property-indicator"></span>
        <span class="property-type">string</span>
    </dt>
    <dd>{{% md %}}{{% /md %}}</dd>

    <dt class="property-required"
            title="Required">
        <span>Secret<wbr>Key</span>
        <span class="property-indicator"></span>
        <span class="property-type">string</span>
    </dt>
    <dd>{{% md %}}{{% /md %}}</dd>

    <dt class="property-optional"
            title="Optional">
        <span>Version</span>
        <span class="property-indicator"></span>
        <span class="property-type">string?</span>
    </dt>
    <dd>{{% md %}}{{% /md %}}</dd>

</dl>
{{% /choosable %}}


{{% choosable language go %}}
<dl class="resources-properties">

    <dt class="property-required"
            title="Required">
        <span>Access<wbr>Key</span>
        <span class="property-indicator"></span>
        <span class="property-type">string</span>
    </dt>
    <dd>{{% md %}}{{% /md %}}</dd>

    <dt class="property-required"
            title="Required">
        <span>Master<wbr>Host</span>
        <span class="property-indicator"></span>
        <span class="property-type">string</span>
    </dt>
    <dd>{{% md %}}{{% /md %}}</dd>

    <dt class="property-required"
            title="Required">
        <span>Secret<wbr>Key</span>
        <span class="property-indicator"></span>
        <span class="property-type">string</span>
    </dt>
    <dd>{{% md %}}{{% /md %}}</dd>

    <dt class="property-optional"
            title="Optional">
        <span>Version</span>
        <span class="property-indicator"></span>
        <span class="property-type">*string</span>
    </dt>
    <dd>{{% md %}}{{% /md %}}</dd>

</dl>
{{% /choosable %}}


{{% choosable language nodejs %}}
<dl class="resources-properties">

    <dt class="property-required"
            title="Required">
        <span>access<wbr>Key</span>
        <span class="property-indicator"></span>
        <span class="property-type">string</span>
    </dt>
    <dd>{{% md %}}{{% /md %}}</dd>

    <dt class="property-required"
            title="Required">
        <span>master<wbr>Host</span>
        <span class="property-indicator"></span>
        <span class="property-type">string</span>
    </dt>
    <dd>{{% md %}}{{% /md %}}</dd>

    <dt class="property-required"
            title="Required">
        <span>secret<wbr>Key</span>
        <span class="property-indicator"></span>
        <span class="property-type">string</span>
    </dt>
    <dd>{{% md %}}{{% /md %}}</dd>

    <dt class="property-optional"
            title="Optional">
        <span>version</span>
        <span class="property-indicator"></span>
        <span class="property-type">string?</span>
    </dt>
    <dd>{{% md %}}{{% /md %}}</dd>

</dl>
{{% /choosable %}}


{{% choosable language python %}}
<dl class="resources-properties">

    <dt class="property-required"
            title="Required">
        <span>access<wbr>Key</span>
        <span class="property-indicator"></span>
        <span class="property-type">str</span>
    </dt>
    <dd>{{% md %}}{{% /md %}}</dd>

    <dt class="property-required"
            title="Required">
        <span>master<wbr>Host</span>
        <span class="property-indicator"></span>
        <span class="property-type">str</span>
    </dt>
    <dd>{{% md %}}{{% /md %}}</dd>

    <dt class="property-required"
            title="Required">
        <span>secret<wbr>Key</span>
        <span class="property-indicator"></span>
        <span class="property-type">str</span>
    </dt>
    <dd>{{% md %}}{{% /md %}}</dd>

    <dt class="property-optional"
            title="Optional">
        <span>version</span>
        <span class="property-indicator"></span>
        <span class="property-type">str</span>
    </dt>
    <dd>{{% md %}}{{% /md %}}</dd>

</dl>
{{% /choosable %}}





<h4>Elastigroup<wbr>Integration<wbr>Route53</h4>
{{% choosable language nodejs %}}
> See the <a href="/docs/reference/pkg/nodejs/pulumi/spotinst/types/input/#ElastigroupIntegrationRoute53">input</a> and <a href="/docs/reference/pkg/nodejs/pulumi/spotinst/types/output/#ElastigroupIntegrationRoute53">output</a> API doc for this type.
{{% /choosable %}}

{{% choosable language go %}}
> See the <a href="https://pkg.go.dev/github.com/pulumi/pulumi-spotinst/sdk/go/spotinst/aws?tab=doc#ElastigroupIntegrationRoute53Args">input</a> and <a href="https://pkg.go.dev/github.com/pulumi/pulumi-spotinst/sdk/go/spotinst/aws?tab=doc#ElastigroupIntegrationRoute53Output">output</a> API doc for this type.
{{% /choosable %}}




{{% choosable language csharp %}}
<dl class="resources-properties">

    <dt class="property-required"
            title="Required">
        <span>Domains</span>
        <span class="property-indicator"></span>
        <span class="property-type"><a href="#elastigroupintegrationroute53domain">List&lt;Elastigroup<wbr>Integration<wbr>Route53Domain<wbr>Args&gt;</a></span>
    </dt>
    <dd>{{% md %}}{{% /md %}}</dd>

</dl>
{{% /choosable %}}


{{% choosable language go %}}
<dl class="resources-properties">

    <dt class="property-required"
            title="Required">
        <span>Domains</span>
        <span class="property-indicator"></span>
        <span class="property-type"><a href="#elastigroupintegrationroute53domain">[]Elastigroup<wbr>Integration<wbr>Route53Domain</a></span>
    </dt>
    <dd>{{% md %}}{{% /md %}}</dd>

</dl>
{{% /choosable %}}


{{% choosable language nodejs %}}
<dl class="resources-properties">

    <dt class="property-required"
            title="Required">
        <span>domains</span>
        <span class="property-indicator"></span>
        <span class="property-type"><a href="#elastigroupintegrationroute53domain">Elastigroup<wbr>Integration<wbr>Route53Domain[]</a></span>
    </dt>
    <dd>{{% md %}}{{% /md %}}</dd>

</dl>
{{% /choosable %}}


{{% choosable language python %}}
<dl class="resources-properties">

    <dt class="property-required"
            title="Required">
        <span>domains</span>
        <span class="property-indicator"></span>
        <span class="property-type"><a href="#elastigroupintegrationroute53domain">List[Elastigroup<wbr>Integration<wbr>Route53Domain]</a></span>
    </dt>
    <dd>{{% md %}}{{% /md %}}</dd>

</dl>
{{% /choosable %}}





<h4>Elastigroup<wbr>Integration<wbr>Route53Domain</h4>
{{% choosable language nodejs %}}
> See the <a href="/docs/reference/pkg/nodejs/pulumi/spotinst/types/input/#ElastigroupIntegrationRoute53Domain">input</a> and <a href="/docs/reference/pkg/nodejs/pulumi/spotinst/types/output/#ElastigroupIntegrationRoute53Domain">output</a> API doc for this type.
{{% /choosable %}}

{{% choosable language go %}}
> See the <a href="https://pkg.go.dev/github.com/pulumi/pulumi-spotinst/sdk/go/spotinst/aws?tab=doc#ElastigroupIntegrationRoute53DomainArgs">input</a> and <a href="https://pkg.go.dev/github.com/pulumi/pulumi-spotinst/sdk/go/spotinst/aws?tab=doc#ElastigroupIntegrationRoute53DomainOutput">output</a> API doc for this type.
{{% /choosable %}}




{{% choosable language csharp %}}
<dl class="resources-properties">

    <dt class="property-required"
            title="Required">
        <span>Hosted<wbr>Zone<wbr>Id</span>
        <span class="property-indicator"></span>
        <span class="property-type">string</span>
    </dt>
    <dd>{{% md %}}{{% /md %}}</dd>

    <dt class="property-required"
            title="Required">
        <span>Record<wbr>Sets</span>
        <span class="property-indicator"></span>
        <span class="property-type"><a href="#elastigroupintegrationroute53domainrecordset">List&lt;Elastigroup<wbr>Integration<wbr>Route53Domain<wbr>Record<wbr>Set<wbr>Args&gt;</a></span>
    </dt>
    <dd>{{% md %}}{{% /md %}}</dd>

    <dt class="property-optional"
            title="Optional">
        <span>Spotinst<wbr>Acct<wbr>Id</span>
        <span class="property-indicator"></span>
        <span class="property-type">string?</span>
    </dt>
    <dd>{{% md %}}{{% /md %}}</dd>

</dl>
{{% /choosable %}}


{{% choosable language go %}}
<dl class="resources-properties">

    <dt class="property-required"
            title="Required">
        <span>Hosted<wbr>Zone<wbr>Id</span>
        <span class="property-indicator"></span>
        <span class="property-type">string</span>
    </dt>
    <dd>{{% md %}}{{% /md %}}</dd>

    <dt class="property-required"
            title="Required">
        <span>Record<wbr>Sets</span>
        <span class="property-indicator"></span>
        <span class="property-type"><a href="#elastigroupintegrationroute53domainrecordset">[]Elastigroup<wbr>Integration<wbr>Route53Domain<wbr>Record<wbr>Set</a></span>
    </dt>
    <dd>{{% md %}}{{% /md %}}</dd>

    <dt class="property-optional"
            title="Optional">
        <span>Spotinst<wbr>Acct<wbr>Id</span>
        <span class="property-indicator"></span>
        <span class="property-type">*string</span>
    </dt>
    <dd>{{% md %}}{{% /md %}}</dd>

</dl>
{{% /choosable %}}


{{% choosable language nodejs %}}
<dl class="resources-properties">

    <dt class="property-required"
            title="Required">
        <span>hosted<wbr>Zone<wbr>Id</span>
        <span class="property-indicator"></span>
        <span class="property-type">string</span>
    </dt>
    <dd>{{% md %}}{{% /md %}}</dd>

    <dt class="property-required"
            title="Required">
        <span>record<wbr>Sets</span>
        <span class="property-indicator"></span>
        <span class="property-type"><a href="#elastigroupintegrationroute53domainrecordset">Elastigroup<wbr>Integration<wbr>Route53Domain<wbr>Record<wbr>Set[]</a></span>
    </dt>
    <dd>{{% md %}}{{% /md %}}</dd>

    <dt class="property-optional"
            title="Optional">
        <span>spotinst<wbr>Acct<wbr>Id</span>
        <span class="property-indicator"></span>
        <span class="property-type">string?</span>
    </dt>
    <dd>{{% md %}}{{% /md %}}</dd>

</dl>
{{% /choosable %}}


{{% choosable language python %}}
<dl class="resources-properties">

    <dt class="property-required"
            title="Required">
        <span>hosted<wbr>Zone<wbr>Id</span>
        <span class="property-indicator"></span>
        <span class="property-type">str</span>
    </dt>
    <dd>{{% md %}}{{% /md %}}</dd>

    <dt class="property-required"
            title="Required">
        <span>record<wbr>Sets</span>
        <span class="property-indicator"></span>
        <span class="property-type"><a href="#elastigroupintegrationroute53domainrecordset">List[Elastigroup<wbr>Integration<wbr>Route53Domain<wbr>Record<wbr>Set]</a></span>
    </dt>
    <dd>{{% md %}}{{% /md %}}</dd>

    <dt class="property-optional"
            title="Optional">
        <span>spotinst<wbr>Acct<wbr>Id</span>
        <span class="property-indicator"></span>
        <span class="property-type">str</span>
    </dt>
    <dd>{{% md %}}{{% /md %}}</dd>

</dl>
{{% /choosable %}}





<h4>Elastigroup<wbr>Integration<wbr>Route53Domain<wbr>Record<wbr>Set</h4>
{{% choosable language nodejs %}}
> See the <a href="/docs/reference/pkg/nodejs/pulumi/spotinst/types/input/#ElastigroupIntegrationRoute53DomainRecordSet">input</a> and <a href="/docs/reference/pkg/nodejs/pulumi/spotinst/types/output/#ElastigroupIntegrationRoute53DomainRecordSet">output</a> API doc for this type.
{{% /choosable %}}

{{% choosable language go %}}
> See the <a href="https://pkg.go.dev/github.com/pulumi/pulumi-spotinst/sdk/go/spotinst/aws?tab=doc#ElastigroupIntegrationRoute53DomainRecordSetArgs">input</a> and <a href="https://pkg.go.dev/github.com/pulumi/pulumi-spotinst/sdk/go/spotinst/aws?tab=doc#ElastigroupIntegrationRoute53DomainRecordSetOutput">output</a> API doc for this type.
{{% /choosable %}}




{{% choosable language csharp %}}
<dl class="resources-properties">

    <dt class="property-required"
            title="Required">
        <span>Name</span>
        <span class="property-indicator"></span>
        <span class="property-type">string</span>
    </dt>
    <dd>{{% md %}}The group name.
{{% /md %}}</dd>

    <dt class="property-optional"
            title="Optional">
        <span>Use<wbr>Public<wbr>Ip</span>
        <span class="property-indicator"></span>
        <span class="property-type">bool?</span>
    </dt>
    <dd>{{% md %}}{{% /md %}}</dd>

</dl>
{{% /choosable %}}


{{% choosable language go %}}
<dl class="resources-properties">

    <dt class="property-required"
            title="Required">
        <span>Name</span>
        <span class="property-indicator"></span>
        <span class="property-type">string</span>
    </dt>
    <dd>{{% md %}}The group name.
{{% /md %}}</dd>

    <dt class="property-optional"
            title="Optional">
        <span>Use<wbr>Public<wbr>Ip</span>
        <span class="property-indicator"></span>
        <span class="property-type">*bool</span>
    </dt>
    <dd>{{% md %}}{{% /md %}}</dd>

</dl>
{{% /choosable %}}


{{% choosable language nodejs %}}
<dl class="resources-properties">

    <dt class="property-required"
            title="Required">
        <span>name</span>
        <span class="property-indicator"></span>
        <span class="property-type">string</span>
    </dt>
    <dd>{{% md %}}The group name.
{{% /md %}}</dd>

    <dt class="property-optional"
            title="Optional">
        <span>use<wbr>Public<wbr>Ip</span>
        <span class="property-indicator"></span>
        <span class="property-type">boolean?</span>
    </dt>
    <dd>{{% md %}}{{% /md %}}</dd>

</dl>
{{% /choosable %}}


{{% choosable language python %}}
<dl class="resources-properties">

    <dt class="property-required"
            title="Required">
        <span>name</span>
        <span class="property-indicator"></span>
        <span class="property-type">str</span>
    </dt>
    <dd>{{% md %}}The group name.
{{% /md %}}</dd>

    <dt class="property-optional"
            title="Optional">
        <span>use<wbr>Public<wbr>Ip</span>
        <span class="property-indicator"></span>
        <span class="property-type">bool</span>
    </dt>
    <dd>{{% md %}}{{% /md %}}</dd>

</dl>
{{% /choosable %}}





<h4>Elastigroup<wbr>Multai<wbr>Target<wbr>Set</h4>
{{% choosable language nodejs %}}
> See the <a href="/docs/reference/pkg/nodejs/pulumi/spotinst/types/input/#ElastigroupMultaiTargetSet">input</a> and <a href="/docs/reference/pkg/nodejs/pulumi/spotinst/types/output/#ElastigroupMultaiTargetSet">output</a> API doc for this type.
{{% /choosable %}}

{{% choosable language go %}}
> See the <a href="https://pkg.go.dev/github.com/pulumi/pulumi-spotinst/sdk/go/spotinst/aws?tab=doc#ElastigroupMultaiTargetSetArgs">input</a> and <a href="https://pkg.go.dev/github.com/pulumi/pulumi-spotinst/sdk/go/spotinst/aws?tab=doc#ElastigroupMultaiTargetSetOutput">output</a> API doc for this type.
{{% /choosable %}}




{{% choosable language csharp %}}
<dl class="resources-properties">

    <dt class="property-required"
            title="Required">
        <span>Balancer<wbr>Id</span>
        <span class="property-indicator"></span>
        <span class="property-type">string</span>
    </dt>
    <dd>{{% md %}}{{% /md %}}</dd>

    <dt class="property-required"
            title="Required">
        <span>Target<wbr>Set<wbr>Id</span>
        <span class="property-indicator"></span>
        <span class="property-type">string</span>
    </dt>
    <dd>{{% md %}}{{% /md %}}</dd>

</dl>
{{% /choosable %}}


{{% choosable language go %}}
<dl class="resources-properties">

    <dt class="property-required"
            title="Required">
        <span>Balancer<wbr>Id</span>
        <span class="property-indicator"></span>
        <span class="property-type">string</span>
    </dt>
    <dd>{{% md %}}{{% /md %}}</dd>

    <dt class="property-required"
            title="Required">
        <span>Target<wbr>Set<wbr>Id</span>
        <span class="property-indicator"></span>
        <span class="property-type">string</span>
    </dt>
    <dd>{{% md %}}{{% /md %}}</dd>

</dl>
{{% /choosable %}}


{{% choosable language nodejs %}}
<dl class="resources-properties">

    <dt class="property-required"
            title="Required">
        <span>balancer<wbr>Id</span>
        <span class="property-indicator"></span>
        <span class="property-type">string</span>
    </dt>
    <dd>{{% md %}}{{% /md %}}</dd>

    <dt class="property-required"
            title="Required">
        <span>target<wbr>Set<wbr>Id</span>
        <span class="property-indicator"></span>
        <span class="property-type">string</span>
    </dt>
    <dd>{{% md %}}{{% /md %}}</dd>

</dl>
{{% /choosable %}}


{{% choosable language python %}}
<dl class="resources-properties">

    <dt class="property-required"
            title="Required">
        <span>balancer_<wbr>id</span>
        <span class="property-indicator"></span>
        <span class="property-type">str</span>
    </dt>
    <dd>{{% md %}}{{% /md %}}</dd>

    <dt class="property-required"
            title="Required">
        <span>target_<wbr>set_<wbr>id</span>
        <span class="property-indicator"></span>
        <span class="property-type">str</span>
    </dt>
    <dd>{{% md %}}{{% /md %}}</dd>

</dl>
{{% /choosable %}}





<h4>Elastigroup<wbr>Network<wbr>Interface</h4>
{{% choosable language nodejs %}}
> See the <a href="/docs/reference/pkg/nodejs/pulumi/spotinst/types/input/#ElastigroupNetworkInterface">input</a> and <a href="/docs/reference/pkg/nodejs/pulumi/spotinst/types/output/#ElastigroupNetworkInterface">output</a> API doc for this type.
{{% /choosable %}}

{{% choosable language go %}}
> See the <a href="https://pkg.go.dev/github.com/pulumi/pulumi-spotinst/sdk/go/spotinst/aws?tab=doc#ElastigroupNetworkInterfaceArgs">input</a> and <a href="https://pkg.go.dev/github.com/pulumi/pulumi-spotinst/sdk/go/spotinst/aws?tab=doc#ElastigroupNetworkInterfaceOutput">output</a> API doc for this type.
{{% /choosable %}}




{{% choosable language csharp %}}
<dl class="resources-properties">

    <dt class="property-optional"
            title="Optional">
        <span>Associate<wbr>Ipv6Address</span>
        <span class="property-indicator"></span>
        <span class="property-type">bool?</span>
    </dt>
    <dd>{{% md %}}{{% /md %}}</dd>

    <dt class="property-optional"
            title="Optional">
        <span>Associate<wbr>Public<wbr>Ip<wbr>Address</span>
        <span class="property-indicator"></span>
        <span class="property-type">bool?</span>
    </dt>
    <dd>{{% md %}}{{% /md %}}</dd>

    <dt class="property-optional"
            title="Optional">
        <span>Delete<wbr>On<wbr>Termination</span>
        <span class="property-indicator"></span>
        <span class="property-type">bool?</span>
    </dt>
    <dd>{{% md %}}{{% /md %}}</dd>

    <dt class="property-optional"
            title="Optional">
        <span>Description</span>
        <span class="property-indicator"></span>
        <span class="property-type">string?</span>
    </dt>
    <dd>{{% md %}}The group description.
{{% /md %}}</dd>

    <dt class="property-required"
            title="Required">
        <span>Device<wbr>Index</span>
        <span class="property-indicator"></span>
        <span class="property-type">string</span>
    </dt>
    <dd>{{% md %}}{{% /md %}}</dd>

    <dt class="property-optional"
            title="Optional">
        <span>Network<wbr>Interface<wbr>Id</span>
        <span class="property-indicator"></span>
        <span class="property-type">string?</span>
    </dt>
    <dd>{{% md %}}{{% /md %}}</dd>

    <dt class="property-optional"
            title="Optional">
        <span>Private<wbr>Ip<wbr>Address</span>
        <span class="property-indicator"></span>
        <span class="property-type">string?</span>
    </dt>
    <dd>{{% md %}}{{% /md %}}</dd>

    <dt class="property-optional"
            title="Optional">
        <span>Secondary<wbr>Private<wbr>Ip<wbr>Address<wbr>Count</span>
        <span class="property-indicator"></span>
        <span class="property-type">string?</span>
    </dt>
    <dd>{{% md %}}{{% /md %}}</dd>

</dl>
{{% /choosable %}}


{{% choosable language go %}}
<dl class="resources-properties">

    <dt class="property-optional"
            title="Optional">
        <span>Associate<wbr>Ipv6Address</span>
        <span class="property-indicator"></span>
        <span class="property-type">*bool</span>
    </dt>
    <dd>{{% md %}}{{% /md %}}</dd>

    <dt class="property-optional"
            title="Optional">
        <span>Associate<wbr>Public<wbr>Ip<wbr>Address</span>
        <span class="property-indicator"></span>
        <span class="property-type">*bool</span>
    </dt>
    <dd>{{% md %}}{{% /md %}}</dd>

    <dt class="property-optional"
            title="Optional">
        <span>Delete<wbr>On<wbr>Termination</span>
        <span class="property-indicator"></span>
        <span class="property-type">*bool</span>
    </dt>
    <dd>{{% md %}}{{% /md %}}</dd>

    <dt class="property-optional"
            title="Optional">
        <span>Description</span>
        <span class="property-indicator"></span>
        <span class="property-type">*string</span>
    </dt>
    <dd>{{% md %}}The group description.
{{% /md %}}</dd>

    <dt class="property-required"
            title="Required">
        <span>Device<wbr>Index</span>
        <span class="property-indicator"></span>
        <span class="property-type">string</span>
    </dt>
    <dd>{{% md %}}{{% /md %}}</dd>

    <dt class="property-optional"
            title="Optional">
        <span>Network<wbr>Interface<wbr>Id</span>
        <span class="property-indicator"></span>
        <span class="property-type">*string</span>
    </dt>
    <dd>{{% md %}}{{% /md %}}</dd>

    <dt class="property-optional"
            title="Optional">
        <span>Private<wbr>Ip<wbr>Address</span>
        <span class="property-indicator"></span>
        <span class="property-type">*string</span>
    </dt>
    <dd>{{% md %}}{{% /md %}}</dd>

    <dt class="property-optional"
            title="Optional">
        <span>Secondary<wbr>Private<wbr>Ip<wbr>Address<wbr>Count</span>
        <span class="property-indicator"></span>
        <span class="property-type">*string</span>
    </dt>
    <dd>{{% md %}}{{% /md %}}</dd>

</dl>
{{% /choosable %}}


{{% choosable language nodejs %}}
<dl class="resources-properties">

    <dt class="property-optional"
            title="Optional">
        <span>associate<wbr>Ipv6Address</span>
        <span class="property-indicator"></span>
        <span class="property-type">boolean?</span>
    </dt>
    <dd>{{% md %}}{{% /md %}}</dd>

    <dt class="property-optional"
            title="Optional">
        <span>associate<wbr>Public<wbr>Ip<wbr>Address</span>
        <span class="property-indicator"></span>
        <span class="property-type">boolean?</span>
    </dt>
    <dd>{{% md %}}{{% /md %}}</dd>

    <dt class="property-optional"
            title="Optional">
        <span>delete<wbr>On<wbr>Termination</span>
        <span class="property-indicator"></span>
        <span class="property-type">boolean?</span>
    </dt>
    <dd>{{% md %}}{{% /md %}}</dd>

    <dt class="property-optional"
            title="Optional">
        <span>description</span>
        <span class="property-indicator"></span>
        <span class="property-type">string?</span>
    </dt>
    <dd>{{% md %}}The group description.
{{% /md %}}</dd>

    <dt class="property-required"
            title="Required">
        <span>device<wbr>Index</span>
        <span class="property-indicator"></span>
        <span class="property-type">string</span>
    </dt>
    <dd>{{% md %}}{{% /md %}}</dd>

    <dt class="property-optional"
            title="Optional">
        <span>network<wbr>Interface<wbr>Id</span>
        <span class="property-indicator"></span>
        <span class="property-type">string?</span>
    </dt>
    <dd>{{% md %}}{{% /md %}}</dd>

    <dt class="property-optional"
            title="Optional">
        <span>private<wbr>Ip<wbr>Address</span>
        <span class="property-indicator"></span>
        <span class="property-type">string?</span>
    </dt>
    <dd>{{% md %}}{{% /md %}}</dd>

    <dt class="property-optional"
            title="Optional">
        <span>secondary<wbr>Private<wbr>Ip<wbr>Address<wbr>Count</span>
        <span class="property-indicator"></span>
        <span class="property-type">string?</span>
    </dt>
    <dd>{{% md %}}{{% /md %}}</dd>

</dl>
{{% /choosable %}}


{{% choosable language python %}}
<dl class="resources-properties">

    <dt class="property-optional"
            title="Optional">
        <span>associate<wbr>Ipv6Address</span>
        <span class="property-indicator"></span>
        <span class="property-type">bool</span>
    </dt>
    <dd>{{% md %}}{{% /md %}}</dd>

    <dt class="property-optional"
            title="Optional">
        <span>associate_<wbr>public_<wbr>ip_<wbr>address</span>
        <span class="property-indicator"></span>
        <span class="property-type">bool</span>
    </dt>
    <dd>{{% md %}}{{% /md %}}</dd>

    <dt class="property-optional"
            title="Optional">
        <span>delete<wbr>On<wbr>Termination</span>
        <span class="property-indicator"></span>
        <span class="property-type">bool</span>
    </dt>
    <dd>{{% md %}}{{% /md %}}</dd>

    <dt class="property-optional"
            title="Optional">
        <span>description</span>
        <span class="property-indicator"></span>
        <span class="property-type">str</span>
    </dt>
    <dd>{{% md %}}The group description.
{{% /md %}}</dd>

    <dt class="property-required"
            title="Required">
        <span>device<wbr>Index</span>
        <span class="property-indicator"></span>
        <span class="property-type">str</span>
    </dt>
    <dd>{{% md %}}{{% /md %}}</dd>

    <dt class="property-optional"
            title="Optional">
        <span>network<wbr>Interface<wbr>Id</span>
        <span class="property-indicator"></span>
        <span class="property-type">str</span>
    </dt>
    <dd>{{% md %}}{{% /md %}}</dd>

    <dt class="property-optional"
            title="Optional">
        <span>private<wbr>Ip<wbr>Address</span>
        <span class="property-indicator"></span>
        <span class="property-type">str</span>
    </dt>
    <dd>{{% md %}}{{% /md %}}</dd>

    <dt class="property-optional"
            title="Optional">
        <span>secondary<wbr>Private<wbr>Ip<wbr>Address<wbr>Count</span>
        <span class="property-indicator"></span>
        <span class="property-type">str</span>
    </dt>
    <dd>{{% md %}}{{% /md %}}</dd>

</dl>
{{% /choosable %}}





<h4>Elastigroup<wbr>Revert<wbr>To<wbr>Spot</h4>
{{% choosable language nodejs %}}
> See the <a href="/docs/reference/pkg/nodejs/pulumi/spotinst/types/input/#ElastigroupRevertToSpot">input</a> and <a href="/docs/reference/pkg/nodejs/pulumi/spotinst/types/output/#ElastigroupRevertToSpot">output</a> API doc for this type.
{{% /choosable %}}

{{% choosable language go %}}
> See the <a href="https://pkg.go.dev/github.com/pulumi/pulumi-spotinst/sdk/go/spotinst/aws?tab=doc#ElastigroupRevertToSpotArgs">input</a> and <a href="https://pkg.go.dev/github.com/pulumi/pulumi-spotinst/sdk/go/spotinst/aws?tab=doc#ElastigroupRevertToSpotOutput">output</a> API doc for this type.
{{% /choosable %}}




{{% choosable language csharp %}}
<dl class="resources-properties">

    <dt class="property-required"
            title="Required">
        <span>Perform<wbr>At</span>
        <span class="property-indicator"></span>
        <span class="property-type">string</span>
    </dt>
    <dd>{{% md %}}In the event of a fallback to On-Demand instances, select the time period to revert back to Spot. Supported Arguments – always (default), timeWindow, never. For timeWindow or never to be valid the group must have availabilityOriented OR persistence defined.
{{% /md %}}</dd>

    <dt class="property-optional"
            title="Optional">
        <span>Time<wbr>Windows</span>
        <span class="property-indicator"></span>
        <span class="property-type">List<string>?</span>
    </dt>
    <dd>{{% md %}}Specify a list of time windows for to execute revertToSpot strategy. Time window format: `ddd:hh:mm-ddd:hh:mm`. Example: `Mon:03:00-Wed:02:30`
{{% /md %}}</dd>

</dl>
{{% /choosable %}}


{{% choosable language go %}}
<dl class="resources-properties">

    <dt class="property-required"
            title="Required">
        <span>Perform<wbr>At</span>
        <span class="property-indicator"></span>
        <span class="property-type">string</span>
    </dt>
    <dd>{{% md %}}In the event of a fallback to On-Demand instances, select the time period to revert back to Spot. Supported Arguments – always (default), timeWindow, never. For timeWindow or never to be valid the group must have availabilityOriented OR persistence defined.
{{% /md %}}</dd>

    <dt class="property-optional"
            title="Optional">
        <span>Time<wbr>Windows</span>
        <span class="property-indicator"></span>
        <span class="property-type">[]string</span>
    </dt>
    <dd>{{% md %}}Specify a list of time windows for to execute revertToSpot strategy. Time window format: `ddd:hh:mm-ddd:hh:mm`. Example: `Mon:03:00-Wed:02:30`
{{% /md %}}</dd>

</dl>
{{% /choosable %}}


{{% choosable language nodejs %}}
<dl class="resources-properties">

    <dt class="property-required"
            title="Required">
        <span>perform<wbr>At</span>
        <span class="property-indicator"></span>
        <span class="property-type">string</span>
    </dt>
    <dd>{{% md %}}In the event of a fallback to On-Demand instances, select the time period to revert back to Spot. Supported Arguments – always (default), timeWindow, never. For timeWindow or never to be valid the group must have availabilityOriented OR persistence defined.
{{% /md %}}</dd>

    <dt class="property-optional"
            title="Optional">
        <span>time<wbr>Windows</span>
        <span class="property-indicator"></span>
        <span class="property-type">string[]?</span>
    </dt>
    <dd>{{% md %}}Specify a list of time windows for to execute revertToSpot strategy. Time window format: `ddd:hh:mm-ddd:hh:mm`. Example: `Mon:03:00-Wed:02:30`
{{% /md %}}</dd>

</dl>
{{% /choosable %}}


{{% choosable language python %}}
<dl class="resources-properties">

    <dt class="property-required"
            title="Required">
        <span>perform<wbr>At</span>
        <span class="property-indicator"></span>
        <span class="property-type">str</span>
    </dt>
    <dd>{{% md %}}In the event of a fallback to On-Demand instances, select the time period to revert back to Spot. Supported Arguments – always (default), timeWindow, never. For timeWindow or never to be valid the group must have availabilityOriented OR persistence defined.
{{% /md %}}</dd>

    <dt class="property-optional"
            title="Optional">
        <span>time<wbr>Windows</span>
        <span class="property-indicator"></span>
        <span class="property-type">List[str]</span>
    </dt>
    <dd>{{% md %}}Specify a list of time windows for to execute revertToSpot strategy. Time window format: `ddd:hh:mm-ddd:hh:mm`. Example: `Mon:03:00-Wed:02:30`
{{% /md %}}</dd>

</dl>
{{% /choosable %}}





<h4>Elastigroup<wbr>Scaling<wbr>Down<wbr>Policy</h4>
{{% choosable language nodejs %}}
> See the <a href="/docs/reference/pkg/nodejs/pulumi/spotinst/types/input/#ElastigroupScalingDownPolicy">input</a> and <a href="/docs/reference/pkg/nodejs/pulumi/spotinst/types/output/#ElastigroupScalingDownPolicy">output</a> API doc for this type.
{{% /choosable %}}

{{% choosable language go %}}
> See the <a href="https://pkg.go.dev/github.com/pulumi/pulumi-spotinst/sdk/go/spotinst/aws?tab=doc#ElastigroupScalingDownPolicyArgs">input</a> and <a href="https://pkg.go.dev/github.com/pulumi/pulumi-spotinst/sdk/go/spotinst/aws?tab=doc#ElastigroupScalingDownPolicyOutput">output</a> API doc for this type.
{{% /choosable %}}




{{% choosable language csharp %}}
<dl class="resources-properties">

    <dt class="property-optional"
            title="Optional">
        <span>Action<wbr>Type</span>
        <span class="property-indicator"></span>
        <span class="property-type">string?</span>
    </dt>
    <dd>{{% md %}}{{% /md %}}</dd>

    <dt class="property-optional"
            title="Optional">
        <span>Adjustment</span>
        <span class="property-indicator"></span>
        <span class="property-type">string?</span>
    </dt>
    <dd>{{% md %}}{{% /md %}}</dd>

    <dt class="property-optional"
            title="Optional">
        <span>Cooldown</span>
        <span class="property-indicator"></span>
        <span class="property-type">int?</span>
    </dt>
    <dd>{{% md %}}{{% /md %}}</dd>

    <dt class="property-optional"
            title="Optional">
        <span>Dimensions</span>
        <span class="property-indicator"></span>
        <span class="property-type"><a href="#elastigroupscalingdownpolicydimension">List&lt;Elastigroup<wbr>Scaling<wbr>Down<wbr>Policy<wbr>Dimension<wbr>Args&gt;?</a></span>
    </dt>
    <dd>{{% md %}}{{% /md %}}</dd>

    <dt class="property-optional"
            title="Optional">
        <span>Evaluation<wbr>Periods</span>
        <span class="property-indicator"></span>
        <span class="property-type">int?</span>
    </dt>
    <dd>{{% md %}}{{% /md %}}</dd>

    <dt class="property-optional"
            title="Optional">
        <span>Is<wbr>Enabled</span>
        <span class="property-indicator"></span>
        <span class="property-type">bool?</span>
    </dt>
    <dd>{{% md %}}{{% /md %}}</dd>

    <dt class="property-optional"
            title="Optional">
        <span>Max<wbr>Target<wbr>Capacity</span>
        <span class="property-indicator"></span>
        <span class="property-type">string?</span>
    </dt>
    <dd>{{% md %}}{{% /md %}}</dd>

    <dt class="property-optional"
            title="Optional">
        <span>Maximum</span>
        <span class="property-indicator"></span>
        <span class="property-type">string?</span>
    </dt>
    <dd>{{% md %}}{{% /md %}}</dd>

    <dt class="property-required"
            title="Required">
        <span>Metric<wbr>Name</span>
        <span class="property-indicator"></span>
        <span class="property-type">string</span>
    </dt>
    <dd>{{% md %}}{{% /md %}}</dd>

    <dt class="property-optional"
            title="Optional">
        <span>Min<wbr>Target<wbr>Capacity</span>
        <span class="property-indicator"></span>
        <span class="property-type">string?</span>
    </dt>
    <dd>{{% md %}}{{% /md %}}</dd>

    <dt class="property-optional"
            title="Optional">
        <span>Minimum</span>
        <span class="property-indicator"></span>
        <span class="property-type">string?</span>
    </dt>
    <dd>{{% md %}}{{% /md %}}</dd>

    <dt class="property-required"
            title="Required">
        <span>Namespace</span>
        <span class="property-indicator"></span>
        <span class="property-type">string</span>
    </dt>
    <dd>{{% md %}}{{% /md %}}</dd>

    <dt class="property-optional"
            title="Optional">
        <span>Operator</span>
        <span class="property-indicator"></span>
        <span class="property-type">string?</span>
    </dt>
    <dd>{{% md %}}{{% /md %}}</dd>

    <dt class="property-optional"
            title="Optional">
        <span>Period</span>
        <span class="property-indicator"></span>
        <span class="property-type">int?</span>
    </dt>
    <dd>{{% md %}}{{% /md %}}</dd>

    <dt class="property-required"
            title="Required">
        <span>Policy<wbr>Name</span>
        <span class="property-indicator"></span>
        <span class="property-type">string</span>
    </dt>
    <dd>{{% md %}}{{% /md %}}</dd>

    <dt class="property-optional"
            title="Optional">
        <span>Source</span>
        <span class="property-indicator"></span>
        <span class="property-type">string?</span>
    </dt>
    <dd>{{% md %}}{{% /md %}}</dd>

    <dt class="property-optional"
            title="Optional">
        <span>Statistic</span>
        <span class="property-indicator"></span>
        <span class="property-type">string?</span>
    </dt>
    <dd>{{% md %}}{{% /md %}}</dd>

    <dt class="property-optional"
            title="Optional">
        <span>Target</span>
        <span class="property-indicator"></span>
        <span class="property-type">string?</span>
    </dt>
    <dd>{{% md %}}{{% /md %}}</dd>

    <dt class="property-required"
            title="Required">
        <span>Threshold</span>
        <span class="property-indicator"></span>
        <span class="property-type">double</span>
    </dt>
    <dd>{{% md %}}{{% /md %}}</dd>

    <dt class="property-required"
            title="Required">
        <span>Unit</span>
        <span class="property-indicator"></span>
        <span class="property-type">string</span>
    </dt>
    <dd>{{% md %}}{{% /md %}}</dd>

</dl>
{{% /choosable %}}


{{% choosable language go %}}
<dl class="resources-properties">

    <dt class="property-optional"
            title="Optional">
        <span>Action<wbr>Type</span>
        <span class="property-indicator"></span>
        <span class="property-type">*string</span>
    </dt>
    <dd>{{% md %}}{{% /md %}}</dd>

    <dt class="property-optional"
            title="Optional">
        <span>Adjustment</span>
        <span class="property-indicator"></span>
        <span class="property-type">*string</span>
    </dt>
    <dd>{{% md %}}{{% /md %}}</dd>

    <dt class="property-optional"
            title="Optional">
        <span>Cooldown</span>
        <span class="property-indicator"></span>
        <span class="property-type">*int</span>
    </dt>
    <dd>{{% md %}}{{% /md %}}</dd>

    <dt class="property-optional"
            title="Optional">
        <span>Dimensions</span>
        <span class="property-indicator"></span>
        <span class="property-type"><a href="#elastigroupscalingdownpolicydimension">[]Elastigroup<wbr>Scaling<wbr>Down<wbr>Policy<wbr>Dimension</a></span>
    </dt>
    <dd>{{% md %}}{{% /md %}}</dd>

    <dt class="property-optional"
            title="Optional">
        <span>Evaluation<wbr>Periods</span>
        <span class="property-indicator"></span>
        <span class="property-type">*int</span>
    </dt>
    <dd>{{% md %}}{{% /md %}}</dd>

    <dt class="property-optional"
            title="Optional">
        <span>Is<wbr>Enabled</span>
        <span class="property-indicator"></span>
        <span class="property-type">*bool</span>
    </dt>
    <dd>{{% md %}}{{% /md %}}</dd>

    <dt class="property-optional"
            title="Optional">
        <span>Max<wbr>Target<wbr>Capacity</span>
        <span class="property-indicator"></span>
        <span class="property-type">*string</span>
    </dt>
    <dd>{{% md %}}{{% /md %}}</dd>

    <dt class="property-optional"
            title="Optional">
        <span>Maximum</span>
        <span class="property-indicator"></span>
        <span class="property-type">*string</span>
    </dt>
    <dd>{{% md %}}{{% /md %}}</dd>

    <dt class="property-required"
            title="Required">
        <span>Metric<wbr>Name</span>
        <span class="property-indicator"></span>
        <span class="property-type">string</span>
    </dt>
    <dd>{{% md %}}{{% /md %}}</dd>

    <dt class="property-optional"
            title="Optional">
        <span>Min<wbr>Target<wbr>Capacity</span>
        <span class="property-indicator"></span>
        <span class="property-type">*string</span>
    </dt>
    <dd>{{% md %}}{{% /md %}}</dd>

    <dt class="property-optional"
            title="Optional">
        <span>Minimum</span>
        <span class="property-indicator"></span>
        <span class="property-type">*string</span>
    </dt>
    <dd>{{% md %}}{{% /md %}}</dd>

    <dt class="property-required"
            title="Required">
        <span>Namespace</span>
        <span class="property-indicator"></span>
        <span class="property-type">string</span>
    </dt>
    <dd>{{% md %}}{{% /md %}}</dd>

    <dt class="property-optional"
            title="Optional">
        <span>Operator</span>
        <span class="property-indicator"></span>
        <span class="property-type">*string</span>
    </dt>
    <dd>{{% md %}}{{% /md %}}</dd>

    <dt class="property-optional"
            title="Optional">
        <span>Period</span>
        <span class="property-indicator"></span>
        <span class="property-type">*int</span>
    </dt>
    <dd>{{% md %}}{{% /md %}}</dd>

    <dt class="property-required"
            title="Required">
        <span>Policy<wbr>Name</span>
        <span class="property-indicator"></span>
        <span class="property-type">string</span>
    </dt>
    <dd>{{% md %}}{{% /md %}}</dd>

    <dt class="property-optional"
            title="Optional">
        <span>Source</span>
        <span class="property-indicator"></span>
        <span class="property-type">*string</span>
    </dt>
    <dd>{{% md %}}{{% /md %}}</dd>

    <dt class="property-optional"
            title="Optional">
        <span>Statistic</span>
        <span class="property-indicator"></span>
        <span class="property-type">*string</span>
    </dt>
    <dd>{{% md %}}{{% /md %}}</dd>

    <dt class="property-optional"
            title="Optional">
        <span>Target</span>
        <span class="property-indicator"></span>
        <span class="property-type">*string</span>
    </dt>
    <dd>{{% md %}}{{% /md %}}</dd>

    <dt class="property-required"
            title="Required">
        <span>Threshold</span>
        <span class="property-indicator"></span>
        <span class="property-type">float64</span>
    </dt>
    <dd>{{% md %}}{{% /md %}}</dd>

    <dt class="property-required"
            title="Required">
        <span>Unit</span>
        <span class="property-indicator"></span>
        <span class="property-type">string</span>
    </dt>
    <dd>{{% md %}}{{% /md %}}</dd>

</dl>
{{% /choosable %}}


{{% choosable language nodejs %}}
<dl class="resources-properties">

    <dt class="property-optional"
            title="Optional">
        <span>action<wbr>Type</span>
        <span class="property-indicator"></span>
        <span class="property-type">string?</span>
    </dt>
    <dd>{{% md %}}{{% /md %}}</dd>

    <dt class="property-optional"
            title="Optional">
        <span>adjustment</span>
        <span class="property-indicator"></span>
        <span class="property-type">string?</span>
    </dt>
    <dd>{{% md %}}{{% /md %}}</dd>

    <dt class="property-optional"
            title="Optional">
        <span>cooldown</span>
        <span class="property-indicator"></span>
        <span class="property-type">number?</span>
    </dt>
    <dd>{{% md %}}{{% /md %}}</dd>

    <dt class="property-optional"
            title="Optional">
        <span>dimensions</span>
        <span class="property-indicator"></span>
        <span class="property-type"><a href="#elastigroupscalingdownpolicydimension">Elastigroup<wbr>Scaling<wbr>Down<wbr>Policy<wbr>Dimension[]?</a></span>
    </dt>
    <dd>{{% md %}}{{% /md %}}</dd>

    <dt class="property-optional"
            title="Optional">
        <span>evaluation<wbr>Periods</span>
        <span class="property-indicator"></span>
        <span class="property-type">number?</span>
    </dt>
    <dd>{{% md %}}{{% /md %}}</dd>

    <dt class="property-optional"
            title="Optional">
        <span>is<wbr>Enabled</span>
        <span class="property-indicator"></span>
        <span class="property-type">boolean?</span>
    </dt>
    <dd>{{% md %}}{{% /md %}}</dd>

    <dt class="property-optional"
            title="Optional">
        <span>max<wbr>Target<wbr>Capacity</span>
        <span class="property-indicator"></span>
        <span class="property-type">string?</span>
    </dt>
    <dd>{{% md %}}{{% /md %}}</dd>

    <dt class="property-optional"
            title="Optional">
        <span>maximum</span>
        <span class="property-indicator"></span>
        <span class="property-type">string?</span>
    </dt>
    <dd>{{% md %}}{{% /md %}}</dd>

    <dt class="property-required"
            title="Required">
        <span>metric<wbr>Name</span>
        <span class="property-indicator"></span>
        <span class="property-type">string</span>
    </dt>
    <dd>{{% md %}}{{% /md %}}</dd>

    <dt class="property-optional"
            title="Optional">
        <span>min<wbr>Target<wbr>Capacity</span>
        <span class="property-indicator"></span>
        <span class="property-type">string?</span>
    </dt>
    <dd>{{% md %}}{{% /md %}}</dd>

    <dt class="property-optional"
            title="Optional">
        <span>minimum</span>
        <span class="property-indicator"></span>
        <span class="property-type">string?</span>
    </dt>
    <dd>{{% md %}}{{% /md %}}</dd>

    <dt class="property-required"
            title="Required">
        <span>namespace</span>
        <span class="property-indicator"></span>
        <span class="property-type">string</span>
    </dt>
    <dd>{{% md %}}{{% /md %}}</dd>

    <dt class="property-optional"
            title="Optional">
        <span>operator</span>
        <span class="property-indicator"></span>
        <span class="property-type">string?</span>
    </dt>
    <dd>{{% md %}}{{% /md %}}</dd>

    <dt class="property-optional"
            title="Optional">
        <span>period</span>
        <span class="property-indicator"></span>
        <span class="property-type">number?</span>
    </dt>
    <dd>{{% md %}}{{% /md %}}</dd>

    <dt class="property-required"
            title="Required">
        <span>policy<wbr>Name</span>
        <span class="property-indicator"></span>
        <span class="property-type">string</span>
    </dt>
    <dd>{{% md %}}{{% /md %}}</dd>

    <dt class="property-optional"
            title="Optional">
        <span>source</span>
        <span class="property-indicator"></span>
        <span class="property-type">string?</span>
    </dt>
    <dd>{{% md %}}{{% /md %}}</dd>

    <dt class="property-optional"
            title="Optional">
        <span>statistic</span>
        <span class="property-indicator"></span>
        <span class="property-type">string?</span>
    </dt>
    <dd>{{% md %}}{{% /md %}}</dd>

    <dt class="property-optional"
            title="Optional">
        <span>target</span>
        <span class="property-indicator"></span>
        <span class="property-type">string?</span>
    </dt>
    <dd>{{% md %}}{{% /md %}}</dd>

    <dt class="property-required"
            title="Required">
        <span>threshold</span>
        <span class="property-indicator"></span>
        <span class="property-type">number</span>
    </dt>
    <dd>{{% md %}}{{% /md %}}</dd>

    <dt class="property-required"
            title="Required">
        <span>unit</span>
        <span class="property-indicator"></span>
        <span class="property-type">string</span>
    </dt>
    <dd>{{% md %}}{{% /md %}}</dd>

</dl>
{{% /choosable %}}


{{% choosable language python %}}
<dl class="resources-properties">

    <dt class="property-optional"
            title="Optional">
        <span>action<wbr>Type</span>
        <span class="property-indicator"></span>
        <span class="property-type">str</span>
    </dt>
    <dd>{{% md %}}{{% /md %}}</dd>

    <dt class="property-optional"
            title="Optional">
        <span>adjustment</span>
        <span class="property-indicator"></span>
        <span class="property-type">str</span>
    </dt>
    <dd>{{% md %}}{{% /md %}}</dd>

    <dt class="property-optional"
            title="Optional">
        <span>cooldown</span>
        <span class="property-indicator"></span>
        <span class="property-type">float</span>
    </dt>
    <dd>{{% md %}}{{% /md %}}</dd>

    <dt class="property-optional"
            title="Optional">
        <span>dimensions</span>
        <span class="property-indicator"></span>
        <span class="property-type"><a href="#elastigroupscalingdownpolicydimension">List[Elastigroup<wbr>Scaling<wbr>Down<wbr>Policy<wbr>Dimension]</a></span>
    </dt>
    <dd>{{% md %}}{{% /md %}}</dd>

    <dt class="property-optional"
            title="Optional">
        <span>evaluation<wbr>Periods</span>
        <span class="property-indicator"></span>
        <span class="property-type">float</span>
    </dt>
    <dd>{{% md %}}{{% /md %}}</dd>

    <dt class="property-optional"
            title="Optional">
        <span>is<wbr>Enabled</span>
        <span class="property-indicator"></span>
        <span class="property-type">bool</span>
    </dt>
    <dd>{{% md %}}{{% /md %}}</dd>

    <dt class="property-optional"
            title="Optional">
        <span>max<wbr>Target<wbr>Capacity</span>
        <span class="property-indicator"></span>
        <span class="property-type">str</span>
    </dt>
    <dd>{{% md %}}{{% /md %}}</dd>

    <dt class="property-optional"
            title="Optional">
        <span>maximum</span>
        <span class="property-indicator"></span>
        <span class="property-type">str</span>
    </dt>
    <dd>{{% md %}}{{% /md %}}</dd>

    <dt class="property-required"
            title="Required">
        <span>metric<wbr>Name</span>
        <span class="property-indicator"></span>
        <span class="property-type">str</span>
    </dt>
    <dd>{{% md %}}{{% /md %}}</dd>

    <dt class="property-optional"
            title="Optional">
        <span>min<wbr>Target<wbr>Capacity</span>
        <span class="property-indicator"></span>
        <span class="property-type">str</span>
    </dt>
    <dd>{{% md %}}{{% /md %}}</dd>

    <dt class="property-optional"
            title="Optional">
        <span>minimum</span>
        <span class="property-indicator"></span>
        <span class="property-type">str</span>
    </dt>
    <dd>{{% md %}}{{% /md %}}</dd>

    <dt class="property-required"
            title="Required">
        <span>namespace</span>
        <span class="property-indicator"></span>
        <span class="property-type">str</span>
    </dt>
    <dd>{{% md %}}{{% /md %}}</dd>

    <dt class="property-optional"
            title="Optional">
        <span>operator</span>
        <span class="property-indicator"></span>
        <span class="property-type">str</span>
    </dt>
    <dd>{{% md %}}{{% /md %}}</dd>

    <dt class="property-optional"
            title="Optional">
        <span>period</span>
        <span class="property-indicator"></span>
        <span class="property-type">float</span>
    </dt>
    <dd>{{% md %}}{{% /md %}}</dd>

    <dt class="property-required"
            title="Required">
        <span>policy<wbr>Name</span>
        <span class="property-indicator"></span>
        <span class="property-type">str</span>
    </dt>
    <dd>{{% md %}}{{% /md %}}</dd>

    <dt class="property-optional"
            title="Optional">
        <span>source</span>
        <span class="property-indicator"></span>
        <span class="property-type">str</span>
    </dt>
    <dd>{{% md %}}{{% /md %}}</dd>

    <dt class="property-optional"
            title="Optional">
        <span>statistic</span>
        <span class="property-indicator"></span>
        <span class="property-type">str</span>
    </dt>
    <dd>{{% md %}}{{% /md %}}</dd>

    <dt class="property-optional"
            title="Optional">
        <span>target</span>
        <span class="property-indicator"></span>
        <span class="property-type">str</span>
    </dt>
    <dd>{{% md %}}{{% /md %}}</dd>

    <dt class="property-required"
            title="Required">
        <span>threshold</span>
        <span class="property-indicator"></span>
        <span class="property-type">float</span>
    </dt>
    <dd>{{% md %}}{{% /md %}}</dd>

    <dt class="property-required"
            title="Required">
        <span>unit</span>
        <span class="property-indicator"></span>
        <span class="property-type">str</span>
    </dt>
    <dd>{{% md %}}{{% /md %}}</dd>

</dl>
{{% /choosable %}}





<h4>Elastigroup<wbr>Scaling<wbr>Down<wbr>Policy<wbr>Dimension</h4>
{{% choosable language nodejs %}}
> See the <a href="/docs/reference/pkg/nodejs/pulumi/spotinst/types/input/#ElastigroupScalingDownPolicyDimension">input</a> and <a href="/docs/reference/pkg/nodejs/pulumi/spotinst/types/output/#ElastigroupScalingDownPolicyDimension">output</a> API doc for this type.
{{% /choosable %}}

{{% choosable language go %}}
> See the <a href="https://pkg.go.dev/github.com/pulumi/pulumi-spotinst/sdk/go/spotinst/aws?tab=doc#ElastigroupScalingDownPolicyDimensionArgs">input</a> and <a href="https://pkg.go.dev/github.com/pulumi/pulumi-spotinst/sdk/go/spotinst/aws?tab=doc#ElastigroupScalingDownPolicyDimensionOutput">output</a> API doc for this type.
{{% /choosable %}}




{{% choosable language csharp %}}
<dl class="resources-properties">

    <dt class="property-required"
            title="Required">
        <span>Name</span>
        <span class="property-indicator"></span>
        <span class="property-type">string</span>
    </dt>
    <dd>{{% md %}}The group name.
{{% /md %}}</dd>

    <dt class="property-optional"
            title="Optional">
        <span>Value</span>
        <span class="property-indicator"></span>
        <span class="property-type">string?</span>
    </dt>
    <dd>{{% md %}}{{% /md %}}</dd>

</dl>
{{% /choosable %}}


{{% choosable language go %}}
<dl class="resources-properties">

    <dt class="property-required"
            title="Required">
        <span>Name</span>
        <span class="property-indicator"></span>
        <span class="property-type">string</span>
    </dt>
    <dd>{{% md %}}The group name.
{{% /md %}}</dd>

    <dt class="property-optional"
            title="Optional">
        <span>Value</span>
        <span class="property-indicator"></span>
        <span class="property-type">*string</span>
    </dt>
    <dd>{{% md %}}{{% /md %}}</dd>

</dl>
{{% /choosable %}}


{{% choosable language nodejs %}}
<dl class="resources-properties">

    <dt class="property-required"
            title="Required">
        <span>name</span>
        <span class="property-indicator"></span>
        <span class="property-type">string</span>
    </dt>
    <dd>{{% md %}}The group name.
{{% /md %}}</dd>

    <dt class="property-optional"
            title="Optional">
        <span>value</span>
        <span class="property-indicator"></span>
        <span class="property-type">string?</span>
    </dt>
    <dd>{{% md %}}{{% /md %}}</dd>

</dl>
{{% /choosable %}}


{{% choosable language python %}}
<dl class="resources-properties">

    <dt class="property-required"
            title="Required">
        <span>name</span>
        <span class="property-indicator"></span>
        <span class="property-type">str</span>
    </dt>
    <dd>{{% md %}}The group name.
{{% /md %}}</dd>

    <dt class="property-optional"
            title="Optional">
        <span>value</span>
        <span class="property-indicator"></span>
        <span class="property-type">str</span>
    </dt>
    <dd>{{% md %}}{{% /md %}}</dd>

</dl>
{{% /choosable %}}





<h4>Elastigroup<wbr>Scaling<wbr>Strategy</h4>
{{% choosable language nodejs %}}
> See the <a href="/docs/reference/pkg/nodejs/pulumi/spotinst/types/input/#ElastigroupScalingStrategy">input</a> and <a href="/docs/reference/pkg/nodejs/pulumi/spotinst/types/output/#ElastigroupScalingStrategy">output</a> API doc for this type.
{{% /choosable %}}

{{% choosable language go %}}
> See the <a href="https://pkg.go.dev/github.com/pulumi/pulumi-spotinst/sdk/go/spotinst/aws?tab=doc#ElastigroupScalingStrategyArgs">input</a> and <a href="https://pkg.go.dev/github.com/pulumi/pulumi-spotinst/sdk/go/spotinst/aws?tab=doc#ElastigroupScalingStrategyOutput">output</a> API doc for this type.
{{% /choosable %}}




{{% choosable language csharp %}}
<dl class="resources-properties">

    <dt class="property-optional"
            title="Optional">
        <span>Terminate<wbr>At<wbr>End<wbr>Of<wbr>Billing<wbr>Hour</span>
        <span class="property-indicator"></span>
        <span class="property-type">bool?</span>
    </dt>
    <dd>{{% md %}}Specify whether to terminate instances at the end of each billing hour.
{{% /md %}}</dd>

    <dt class="property-optional"
            title="Optional">
        <span>Termination<wbr>Policy</span>
        <span class="property-indicator"></span>
        <span class="property-type">string?</span>
    </dt>
    <dd>{{% md %}}- Determines whether to terminate the newest instances when performing a scaling action. Valid values: `"default"`, `"newestInstance"`.
{{% /md %}}</dd>

</dl>
{{% /choosable %}}


{{% choosable language go %}}
<dl class="resources-properties">

    <dt class="property-optional"
            title="Optional">
        <span>Terminate<wbr>At<wbr>End<wbr>Of<wbr>Billing<wbr>Hour</span>
        <span class="property-indicator"></span>
        <span class="property-type">*bool</span>
    </dt>
    <dd>{{% md %}}Specify whether to terminate instances at the end of each billing hour.
{{% /md %}}</dd>

    <dt class="property-optional"
            title="Optional">
        <span>Termination<wbr>Policy</span>
        <span class="property-indicator"></span>
        <span class="property-type">*string</span>
    </dt>
    <dd>{{% md %}}- Determines whether to terminate the newest instances when performing a scaling action. Valid values: `"default"`, `"newestInstance"`.
{{% /md %}}</dd>

</dl>
{{% /choosable %}}


{{% choosable language nodejs %}}
<dl class="resources-properties">

    <dt class="property-optional"
            title="Optional">
        <span>terminate<wbr>At<wbr>End<wbr>Of<wbr>Billing<wbr>Hour</span>
        <span class="property-indicator"></span>
        <span class="property-type">boolean?</span>
    </dt>
    <dd>{{% md %}}Specify whether to terminate instances at the end of each billing hour.
{{% /md %}}</dd>

    <dt class="property-optional"
            title="Optional">
        <span>termination<wbr>Policy</span>
        <span class="property-indicator"></span>
        <span class="property-type">string?</span>
    </dt>
    <dd>{{% md %}}- Determines whether to terminate the newest instances when performing a scaling action. Valid values: `"default"`, `"newestInstance"`.
{{% /md %}}</dd>

</dl>
{{% /choosable %}}


{{% choosable language python %}}
<dl class="resources-properties">

    <dt class="property-optional"
            title="Optional">
        <span>terminate<wbr>At<wbr>End<wbr>Of<wbr>Billing<wbr>Hour</span>
        <span class="property-indicator"></span>
        <span class="property-type">bool</span>
    </dt>
    <dd>{{% md %}}Specify whether to terminate instances at the end of each billing hour.
{{% /md %}}</dd>

    <dt class="property-optional"
            title="Optional">
        <span>termination<wbr>Policy</span>
        <span class="property-indicator"></span>
        <span class="property-type">str</span>
    </dt>
    <dd>{{% md %}}- Determines whether to terminate the newest instances when performing a scaling action. Valid values: `"default"`, `"newestInstance"`.
{{% /md %}}</dd>

</dl>
{{% /choosable %}}





<h4>Elastigroup<wbr>Scaling<wbr>Target<wbr>Policy</h4>
{{% choosable language nodejs %}}
> See the <a href="/docs/reference/pkg/nodejs/pulumi/spotinst/types/input/#ElastigroupScalingTargetPolicy">input</a> and <a href="/docs/reference/pkg/nodejs/pulumi/spotinst/types/output/#ElastigroupScalingTargetPolicy">output</a> API doc for this type.
{{% /choosable %}}

{{% choosable language go %}}
> See the <a href="https://pkg.go.dev/github.com/pulumi/pulumi-spotinst/sdk/go/spotinst/aws?tab=doc#ElastigroupScalingTargetPolicyArgs">input</a> and <a href="https://pkg.go.dev/github.com/pulumi/pulumi-spotinst/sdk/go/spotinst/aws?tab=doc#ElastigroupScalingTargetPolicyOutput">output</a> API doc for this type.
{{% /choosable %}}




{{% choosable language csharp %}}
<dl class="resources-properties">

    <dt class="property-optional"
            title="Optional">
        <span>Cooldown</span>
        <span class="property-indicator"></span>
        <span class="property-type">int?</span>
    </dt>
    <dd>{{% md %}}{{% /md %}}</dd>

    <dt class="property-optional"
            title="Optional">
        <span>Dimensions</span>
        <span class="property-indicator"></span>
        <span class="property-type"><a href="#elastigroupscalingtargetpolicydimension">List&lt;Elastigroup<wbr>Scaling<wbr>Target<wbr>Policy<wbr>Dimension<wbr>Args&gt;?</a></span>
    </dt>
    <dd>{{% md %}}{{% /md %}}</dd>

    <dt class="property-required"
            title="Required">
        <span>Metric<wbr>Name</span>
        <span class="property-indicator"></span>
        <span class="property-type">string</span>
    </dt>
    <dd>{{% md %}}{{% /md %}}</dd>

    <dt class="property-required"
            title="Required">
        <span>Namespace</span>
        <span class="property-indicator"></span>
        <span class="property-type">string</span>
    </dt>
    <dd>{{% md %}}{{% /md %}}</dd>

    <dt class="property-required"
            title="Required">
        <span>Policy<wbr>Name</span>
        <span class="property-indicator"></span>
        <span class="property-type">string</span>
    </dt>
    <dd>{{% md %}}{{% /md %}}</dd>

    <dt class="property-optional"
            title="Optional">
        <span>Predictive<wbr>Mode</span>
        <span class="property-indicator"></span>
        <span class="property-type">string?</span>
    </dt>
    <dd>{{% md %}}{{% /md %}}</dd>

    <dt class="property-optional"
            title="Optional">
        <span>Source</span>
        <span class="property-indicator"></span>
        <span class="property-type">string?</span>
    </dt>
    <dd>{{% md %}}{{% /md %}}</dd>

    <dt class="property-optional"
            title="Optional">
        <span>Statistic</span>
        <span class="property-indicator"></span>
        <span class="property-type">string?</span>
    </dt>
    <dd>{{% md %}}{{% /md %}}</dd>

    <dt class="property-required"
            title="Required">
        <span>Target</span>
        <span class="property-indicator"></span>
        <span class="property-type">double</span>
    </dt>
    <dd>{{% md %}}{{% /md %}}</dd>

    <dt class="property-required"
            title="Required">
        <span>Unit</span>
        <span class="property-indicator"></span>
        <span class="property-type">string</span>
    </dt>
    <dd>{{% md %}}{{% /md %}}</dd>

</dl>
{{% /choosable %}}


{{% choosable language go %}}
<dl class="resources-properties">

    <dt class="property-optional"
            title="Optional">
        <span>Cooldown</span>
        <span class="property-indicator"></span>
        <span class="property-type">*int</span>
    </dt>
    <dd>{{% md %}}{{% /md %}}</dd>

    <dt class="property-optional"
            title="Optional">
        <span>Dimensions</span>
        <span class="property-indicator"></span>
        <span class="property-type"><a href="#elastigroupscalingtargetpolicydimension">[]Elastigroup<wbr>Scaling<wbr>Target<wbr>Policy<wbr>Dimension</a></span>
    </dt>
    <dd>{{% md %}}{{% /md %}}</dd>

    <dt class="property-required"
            title="Required">
        <span>Metric<wbr>Name</span>
        <span class="property-indicator"></span>
        <span class="property-type">string</span>
    </dt>
    <dd>{{% md %}}{{% /md %}}</dd>

    <dt class="property-required"
            title="Required">
        <span>Namespace</span>
        <span class="property-indicator"></span>
        <span class="property-type">string</span>
    </dt>
    <dd>{{% md %}}{{% /md %}}</dd>

    <dt class="property-required"
            title="Required">
        <span>Policy<wbr>Name</span>
        <span class="property-indicator"></span>
        <span class="property-type">string</span>
    </dt>
    <dd>{{% md %}}{{% /md %}}</dd>

    <dt class="property-optional"
            title="Optional">
        <span>Predictive<wbr>Mode</span>
        <span class="property-indicator"></span>
        <span class="property-type">*string</span>
    </dt>
    <dd>{{% md %}}{{% /md %}}</dd>

    <dt class="property-optional"
            title="Optional">
        <span>Source</span>
        <span class="property-indicator"></span>
        <span class="property-type">*string</span>
    </dt>
    <dd>{{% md %}}{{% /md %}}</dd>

    <dt class="property-optional"
            title="Optional">
        <span>Statistic</span>
        <span class="property-indicator"></span>
        <span class="property-type">*string</span>
    </dt>
    <dd>{{% md %}}{{% /md %}}</dd>

    <dt class="property-required"
            title="Required">
        <span>Target</span>
        <span class="property-indicator"></span>
        <span class="property-type">float64</span>
    </dt>
    <dd>{{% md %}}{{% /md %}}</dd>

    <dt class="property-required"
            title="Required">
        <span>Unit</span>
        <span class="property-indicator"></span>
        <span class="property-type">string</span>
    </dt>
    <dd>{{% md %}}{{% /md %}}</dd>

</dl>
{{% /choosable %}}


{{% choosable language nodejs %}}
<dl class="resources-properties">

    <dt class="property-optional"
            title="Optional">
        <span>cooldown</span>
        <span class="property-indicator"></span>
        <span class="property-type">number?</span>
    </dt>
    <dd>{{% md %}}{{% /md %}}</dd>

    <dt class="property-optional"
            title="Optional">
        <span>dimensions</span>
        <span class="property-indicator"></span>
        <span class="property-type"><a href="#elastigroupscalingtargetpolicydimension">Elastigroup<wbr>Scaling<wbr>Target<wbr>Policy<wbr>Dimension[]?</a></span>
    </dt>
    <dd>{{% md %}}{{% /md %}}</dd>

    <dt class="property-required"
            title="Required">
        <span>metric<wbr>Name</span>
        <span class="property-indicator"></span>
        <span class="property-type">string</span>
    </dt>
    <dd>{{% md %}}{{% /md %}}</dd>

    <dt class="property-required"
            title="Required">
        <span>namespace</span>
        <span class="property-indicator"></span>
        <span class="property-type">string</span>
    </dt>
    <dd>{{% md %}}{{% /md %}}</dd>

    <dt class="property-required"
            title="Required">
        <span>policy<wbr>Name</span>
        <span class="property-indicator"></span>
        <span class="property-type">string</span>
    </dt>
    <dd>{{% md %}}{{% /md %}}</dd>

    <dt class="property-optional"
            title="Optional">
        <span>predictive<wbr>Mode</span>
        <span class="property-indicator"></span>
        <span class="property-type">string?</span>
    </dt>
    <dd>{{% md %}}{{% /md %}}</dd>

    <dt class="property-optional"
            title="Optional">
        <span>source</span>
        <span class="property-indicator"></span>
        <span class="property-type">string?</span>
    </dt>
    <dd>{{% md %}}{{% /md %}}</dd>

    <dt class="property-optional"
            title="Optional">
        <span>statistic</span>
        <span class="property-indicator"></span>
        <span class="property-type">string?</span>
    </dt>
    <dd>{{% md %}}{{% /md %}}</dd>

    <dt class="property-required"
            title="Required">
        <span>target</span>
        <span class="property-indicator"></span>
        <span class="property-type">number</span>
    </dt>
    <dd>{{% md %}}{{% /md %}}</dd>

    <dt class="property-required"
            title="Required">
        <span>unit</span>
        <span class="property-indicator"></span>
        <span class="property-type">string</span>
    </dt>
    <dd>{{% md %}}{{% /md %}}</dd>

</dl>
{{% /choosable %}}


{{% choosable language python %}}
<dl class="resources-properties">

    <dt class="property-optional"
            title="Optional">
        <span>cooldown</span>
        <span class="property-indicator"></span>
        <span class="property-type">float</span>
    </dt>
    <dd>{{% md %}}{{% /md %}}</dd>

    <dt class="property-optional"
            title="Optional">
        <span>dimensions</span>
        <span class="property-indicator"></span>
        <span class="property-type"><a href="#elastigroupscalingtargetpolicydimension">List[Elastigroup<wbr>Scaling<wbr>Target<wbr>Policy<wbr>Dimension]</a></span>
    </dt>
    <dd>{{% md %}}{{% /md %}}</dd>

    <dt class="property-required"
            title="Required">
        <span>metric<wbr>Name</span>
        <span class="property-indicator"></span>
        <span class="property-type">str</span>
    </dt>
    <dd>{{% md %}}{{% /md %}}</dd>

    <dt class="property-required"
            title="Required">
        <span>namespace</span>
        <span class="property-indicator"></span>
        <span class="property-type">str</span>
    </dt>
    <dd>{{% md %}}{{% /md %}}</dd>

    <dt class="property-required"
            title="Required">
        <span>policy<wbr>Name</span>
        <span class="property-indicator"></span>
        <span class="property-type">str</span>
    </dt>
    <dd>{{% md %}}{{% /md %}}</dd>

    <dt class="property-optional"
            title="Optional">
        <span>predictive<wbr>Mode</span>
        <span class="property-indicator"></span>
        <span class="property-type">str</span>
    </dt>
    <dd>{{% md %}}{{% /md %}}</dd>

    <dt class="property-optional"
            title="Optional">
        <span>source</span>
        <span class="property-indicator"></span>
        <span class="property-type">str</span>
    </dt>
    <dd>{{% md %}}{{% /md %}}</dd>

    <dt class="property-optional"
            title="Optional">
        <span>statistic</span>
        <span class="property-indicator"></span>
        <span class="property-type">str</span>
    </dt>
    <dd>{{% md %}}{{% /md %}}</dd>

    <dt class="property-required"
            title="Required">
        <span>target</span>
        <span class="property-indicator"></span>
        <span class="property-type">float</span>
    </dt>
    <dd>{{% md %}}{{% /md %}}</dd>

    <dt class="property-required"
            title="Required">
        <span>unit</span>
        <span class="property-indicator"></span>
        <span class="property-type">str</span>
    </dt>
    <dd>{{% md %}}{{% /md %}}</dd>

</dl>
{{% /choosable %}}





<h4>Elastigroup<wbr>Scaling<wbr>Target<wbr>Policy<wbr>Dimension</h4>
{{% choosable language nodejs %}}
> See the <a href="/docs/reference/pkg/nodejs/pulumi/spotinst/types/input/#ElastigroupScalingTargetPolicyDimension">input</a> and <a href="/docs/reference/pkg/nodejs/pulumi/spotinst/types/output/#ElastigroupScalingTargetPolicyDimension">output</a> API doc for this type.
{{% /choosable %}}

{{% choosable language go %}}
> See the <a href="https://pkg.go.dev/github.com/pulumi/pulumi-spotinst/sdk/go/spotinst/aws?tab=doc#ElastigroupScalingTargetPolicyDimensionArgs">input</a> and <a href="https://pkg.go.dev/github.com/pulumi/pulumi-spotinst/sdk/go/spotinst/aws?tab=doc#ElastigroupScalingTargetPolicyDimensionOutput">output</a> API doc for this type.
{{% /choosable %}}




{{% choosable language csharp %}}
<dl class="resources-properties">

    <dt class="property-required"
            title="Required">
        <span>Name</span>
        <span class="property-indicator"></span>
        <span class="property-type">string</span>
    </dt>
    <dd>{{% md %}}The group name.
{{% /md %}}</dd>

    <dt class="property-optional"
            title="Optional">
        <span>Value</span>
        <span class="property-indicator"></span>
        <span class="property-type">string?</span>
    </dt>
    <dd>{{% md %}}{{% /md %}}</dd>

</dl>
{{% /choosable %}}


{{% choosable language go %}}
<dl class="resources-properties">

    <dt class="property-required"
            title="Required">
        <span>Name</span>
        <span class="property-indicator"></span>
        <span class="property-type">string</span>
    </dt>
    <dd>{{% md %}}The group name.
{{% /md %}}</dd>

    <dt class="property-optional"
            title="Optional">
        <span>Value</span>
        <span class="property-indicator"></span>
        <span class="property-type">*string</span>
    </dt>
    <dd>{{% md %}}{{% /md %}}</dd>

</dl>
{{% /choosable %}}


{{% choosable language nodejs %}}
<dl class="resources-properties">

    <dt class="property-required"
            title="Required">
        <span>name</span>
        <span class="property-indicator"></span>
        <span class="property-type">string</span>
    </dt>
    <dd>{{% md %}}The group name.
{{% /md %}}</dd>

    <dt class="property-optional"
            title="Optional">
        <span>value</span>
        <span class="property-indicator"></span>
        <span class="property-type">string?</span>
    </dt>
    <dd>{{% md %}}{{% /md %}}</dd>

</dl>
{{% /choosable %}}


{{% choosable language python %}}
<dl class="resources-properties">

    <dt class="property-required"
            title="Required">
        <span>name</span>
        <span class="property-indicator"></span>
        <span class="property-type">str</span>
    </dt>
    <dd>{{% md %}}The group name.
{{% /md %}}</dd>

    <dt class="property-optional"
            title="Optional">
        <span>value</span>
        <span class="property-indicator"></span>
        <span class="property-type">str</span>
    </dt>
    <dd>{{% md %}}{{% /md %}}</dd>

</dl>
{{% /choosable %}}





<h4>Elastigroup<wbr>Scaling<wbr>Up<wbr>Policy</h4>
{{% choosable language nodejs %}}
> See the <a href="/docs/reference/pkg/nodejs/pulumi/spotinst/types/input/#ElastigroupScalingUpPolicy">input</a> and <a href="/docs/reference/pkg/nodejs/pulumi/spotinst/types/output/#ElastigroupScalingUpPolicy">output</a> API doc for this type.
{{% /choosable %}}

{{% choosable language go %}}
> See the <a href="https://pkg.go.dev/github.com/pulumi/pulumi-spotinst/sdk/go/spotinst/aws?tab=doc#ElastigroupScalingUpPolicyArgs">input</a> and <a href="https://pkg.go.dev/github.com/pulumi/pulumi-spotinst/sdk/go/spotinst/aws?tab=doc#ElastigroupScalingUpPolicyOutput">output</a> API doc for this type.
{{% /choosable %}}




{{% choosable language csharp %}}
<dl class="resources-properties">

    <dt class="property-optional"
            title="Optional">
        <span>Action<wbr>Type</span>
        <span class="property-indicator"></span>
        <span class="property-type">string?</span>
    </dt>
    <dd>{{% md %}}{{% /md %}}</dd>

    <dt class="property-optional"
            title="Optional">
        <span>Adjustment</span>
        <span class="property-indicator"></span>
        <span class="property-type">string?</span>
    </dt>
    <dd>{{% md %}}{{% /md %}}</dd>

    <dt class="property-optional"
            title="Optional">
        <span>Cooldown</span>
        <span class="property-indicator"></span>
        <span class="property-type">int?</span>
    </dt>
    <dd>{{% md %}}{{% /md %}}</dd>

    <dt class="property-optional"
            title="Optional">
        <span>Dimensions</span>
        <span class="property-indicator"></span>
        <span class="property-type"><a href="#elastigroupscalinguppolicydimension">List&lt;Elastigroup<wbr>Scaling<wbr>Up<wbr>Policy<wbr>Dimension<wbr>Args&gt;?</a></span>
    </dt>
    <dd>{{% md %}}{{% /md %}}</dd>

    <dt class="property-optional"
            title="Optional">
        <span>Evaluation<wbr>Periods</span>
        <span class="property-indicator"></span>
        <span class="property-type">int?</span>
    </dt>
    <dd>{{% md %}}{{% /md %}}</dd>

    <dt class="property-optional"
            title="Optional">
        <span>Is<wbr>Enabled</span>
        <span class="property-indicator"></span>
        <span class="property-type">bool?</span>
    </dt>
    <dd>{{% md %}}{{% /md %}}</dd>

    <dt class="property-optional"
            title="Optional">
        <span>Max<wbr>Target<wbr>Capacity</span>
        <span class="property-indicator"></span>
        <span class="property-type">string?</span>
    </dt>
    <dd>{{% md %}}{{% /md %}}</dd>

    <dt class="property-optional"
            title="Optional">
        <span>Maximum</span>
        <span class="property-indicator"></span>
        <span class="property-type">string?</span>
    </dt>
    <dd>{{% md %}}{{% /md %}}</dd>

    <dt class="property-required"
            title="Required">
        <span>Metric<wbr>Name</span>
        <span class="property-indicator"></span>
        <span class="property-type">string</span>
    </dt>
    <dd>{{% md %}}{{% /md %}}</dd>

    <dt class="property-optional"
            title="Optional">
        <span>Min<wbr>Target<wbr>Capacity</span>
        <span class="property-indicator"></span>
        <span class="property-type">string?</span>
    </dt>
    <dd>{{% md %}}{{% /md %}}</dd>

    <dt class="property-optional"
            title="Optional">
        <span>Minimum</span>
        <span class="property-indicator"></span>
        <span class="property-type">string?</span>
    </dt>
    <dd>{{% md %}}{{% /md %}}</dd>

    <dt class="property-required"
            title="Required">
        <span>Namespace</span>
        <span class="property-indicator"></span>
        <span class="property-type">string</span>
    </dt>
    <dd>{{% md %}}{{% /md %}}</dd>

    <dt class="property-optional"
            title="Optional">
        <span>Operator</span>
        <span class="property-indicator"></span>
        <span class="property-type">string?</span>
    </dt>
    <dd>{{% md %}}{{% /md %}}</dd>

    <dt class="property-optional"
            title="Optional">
        <span>Period</span>
        <span class="property-indicator"></span>
        <span class="property-type">int?</span>
    </dt>
    <dd>{{% md %}}{{% /md %}}</dd>

    <dt class="property-required"
            title="Required">
        <span>Policy<wbr>Name</span>
        <span class="property-indicator"></span>
        <span class="property-type">string</span>
    </dt>
    <dd>{{% md %}}{{% /md %}}</dd>

    <dt class="property-optional"
            title="Optional">
        <span>Source</span>
        <span class="property-indicator"></span>
        <span class="property-type">string?</span>
    </dt>
    <dd>{{% md %}}{{% /md %}}</dd>

    <dt class="property-optional"
            title="Optional">
        <span>Statistic</span>
        <span class="property-indicator"></span>
        <span class="property-type">string?</span>
    </dt>
    <dd>{{% md %}}{{% /md %}}</dd>

    <dt class="property-optional"
            title="Optional">
        <span>Target</span>
        <span class="property-indicator"></span>
        <span class="property-type">string?</span>
    </dt>
    <dd>{{% md %}}{{% /md %}}</dd>

    <dt class="property-required"
            title="Required">
        <span>Threshold</span>
        <span class="property-indicator"></span>
        <span class="property-type">double</span>
    </dt>
    <dd>{{% md %}}{{% /md %}}</dd>

    <dt class="property-required"
            title="Required">
        <span>Unit</span>
        <span class="property-indicator"></span>
        <span class="property-type">string</span>
    </dt>
    <dd>{{% md %}}{{% /md %}}</dd>

</dl>
{{% /choosable %}}


{{% choosable language go %}}
<dl class="resources-properties">

    <dt class="property-optional"
            title="Optional">
        <span>Action<wbr>Type</span>
        <span class="property-indicator"></span>
        <span class="property-type">*string</span>
    </dt>
    <dd>{{% md %}}{{% /md %}}</dd>

    <dt class="property-optional"
            title="Optional">
        <span>Adjustment</span>
        <span class="property-indicator"></span>
        <span class="property-type">*string</span>
    </dt>
    <dd>{{% md %}}{{% /md %}}</dd>

    <dt class="property-optional"
            title="Optional">
        <span>Cooldown</span>
        <span class="property-indicator"></span>
        <span class="property-type">*int</span>
    </dt>
    <dd>{{% md %}}{{% /md %}}</dd>

    <dt class="property-optional"
            title="Optional">
        <span>Dimensions</span>
        <span class="property-indicator"></span>
        <span class="property-type"><a href="#elastigroupscalinguppolicydimension">[]Elastigroup<wbr>Scaling<wbr>Up<wbr>Policy<wbr>Dimension</a></span>
    </dt>
    <dd>{{% md %}}{{% /md %}}</dd>

    <dt class="property-optional"
            title="Optional">
        <span>Evaluation<wbr>Periods</span>
        <span class="property-indicator"></span>
        <span class="property-type">*int</span>
    </dt>
    <dd>{{% md %}}{{% /md %}}</dd>

    <dt class="property-optional"
            title="Optional">
        <span>Is<wbr>Enabled</span>
        <span class="property-indicator"></span>
        <span class="property-type">*bool</span>
    </dt>
    <dd>{{% md %}}{{% /md %}}</dd>

    <dt class="property-optional"
            title="Optional">
        <span>Max<wbr>Target<wbr>Capacity</span>
        <span class="property-indicator"></span>
        <span class="property-type">*string</span>
    </dt>
    <dd>{{% md %}}{{% /md %}}</dd>

    <dt class="property-optional"
            title="Optional">
        <span>Maximum</span>
        <span class="property-indicator"></span>
        <span class="property-type">*string</span>
    </dt>
    <dd>{{% md %}}{{% /md %}}</dd>

    <dt class="property-required"
            title="Required">
        <span>Metric<wbr>Name</span>
        <span class="property-indicator"></span>
        <span class="property-type">string</span>
    </dt>
    <dd>{{% md %}}{{% /md %}}</dd>

    <dt class="property-optional"
            title="Optional">
        <span>Min<wbr>Target<wbr>Capacity</span>
        <span class="property-indicator"></span>
        <span class="property-type">*string</span>
    </dt>
    <dd>{{% md %}}{{% /md %}}</dd>

    <dt class="property-optional"
            title="Optional">
        <span>Minimum</span>
        <span class="property-indicator"></span>
        <span class="property-type">*string</span>
    </dt>
    <dd>{{% md %}}{{% /md %}}</dd>

    <dt class="property-required"
            title="Required">
        <span>Namespace</span>
        <span class="property-indicator"></span>
        <span class="property-type">string</span>
    </dt>
    <dd>{{% md %}}{{% /md %}}</dd>

    <dt class="property-optional"
            title="Optional">
        <span>Operator</span>
        <span class="property-indicator"></span>
        <span class="property-type">*string</span>
    </dt>
    <dd>{{% md %}}{{% /md %}}</dd>

    <dt class="property-optional"
            title="Optional">
        <span>Period</span>
        <span class="property-indicator"></span>
        <span class="property-type">*int</span>
    </dt>
    <dd>{{% md %}}{{% /md %}}</dd>

    <dt class="property-required"
            title="Required">
        <span>Policy<wbr>Name</span>
        <span class="property-indicator"></span>
        <span class="property-type">string</span>
    </dt>
    <dd>{{% md %}}{{% /md %}}</dd>

    <dt class="property-optional"
            title="Optional">
        <span>Source</span>
        <span class="property-indicator"></span>
        <span class="property-type">*string</span>
    </dt>
    <dd>{{% md %}}{{% /md %}}</dd>

    <dt class="property-optional"
            title="Optional">
        <span>Statistic</span>
        <span class="property-indicator"></span>
        <span class="property-type">*string</span>
    </dt>
    <dd>{{% md %}}{{% /md %}}</dd>

    <dt class="property-optional"
            title="Optional">
        <span>Target</span>
        <span class="property-indicator"></span>
        <span class="property-type">*string</span>
    </dt>
    <dd>{{% md %}}{{% /md %}}</dd>

    <dt class="property-required"
            title="Required">
        <span>Threshold</span>
        <span class="property-indicator"></span>
        <span class="property-type">float64</span>
    </dt>
    <dd>{{% md %}}{{% /md %}}</dd>

    <dt class="property-required"
            title="Required">
        <span>Unit</span>
        <span class="property-indicator"></span>
        <span class="property-type">string</span>
    </dt>
    <dd>{{% md %}}{{% /md %}}</dd>

</dl>
{{% /choosable %}}


{{% choosable language nodejs %}}
<dl class="resources-properties">

    <dt class="property-optional"
            title="Optional">
        <span>action<wbr>Type</span>
        <span class="property-indicator"></span>
        <span class="property-type">string?</span>
    </dt>
    <dd>{{% md %}}{{% /md %}}</dd>

    <dt class="property-optional"
            title="Optional">
        <span>adjustment</span>
        <span class="property-indicator"></span>
        <span class="property-type">string?</span>
    </dt>
    <dd>{{% md %}}{{% /md %}}</dd>

    <dt class="property-optional"
            title="Optional">
        <span>cooldown</span>
        <span class="property-indicator"></span>
        <span class="property-type">number?</span>
    </dt>
    <dd>{{% md %}}{{% /md %}}</dd>

    <dt class="property-optional"
            title="Optional">
        <span>dimensions</span>
        <span class="property-indicator"></span>
        <span class="property-type"><a href="#elastigroupscalinguppolicydimension">Elastigroup<wbr>Scaling<wbr>Up<wbr>Policy<wbr>Dimension[]?</a></span>
    </dt>
    <dd>{{% md %}}{{% /md %}}</dd>

    <dt class="property-optional"
            title="Optional">
        <span>evaluation<wbr>Periods</span>
        <span class="property-indicator"></span>
        <span class="property-type">number?</span>
    </dt>
    <dd>{{% md %}}{{% /md %}}</dd>

    <dt class="property-optional"
            title="Optional">
        <span>is<wbr>Enabled</span>
        <span class="property-indicator"></span>
        <span class="property-type">boolean?</span>
    </dt>
    <dd>{{% md %}}{{% /md %}}</dd>

    <dt class="property-optional"
            title="Optional">
        <span>max<wbr>Target<wbr>Capacity</span>
        <span class="property-indicator"></span>
        <span class="property-type">string?</span>
    </dt>
    <dd>{{% md %}}{{% /md %}}</dd>

    <dt class="property-optional"
            title="Optional">
        <span>maximum</span>
        <span class="property-indicator"></span>
        <span class="property-type">string?</span>
    </dt>
    <dd>{{% md %}}{{% /md %}}</dd>

    <dt class="property-required"
            title="Required">
        <span>metric<wbr>Name</span>
        <span class="property-indicator"></span>
        <span class="property-type">string</span>
    </dt>
    <dd>{{% md %}}{{% /md %}}</dd>

    <dt class="property-optional"
            title="Optional">
        <span>min<wbr>Target<wbr>Capacity</span>
        <span class="property-indicator"></span>
        <span class="property-type">string?</span>
    </dt>
    <dd>{{% md %}}{{% /md %}}</dd>

    <dt class="property-optional"
            title="Optional">
        <span>minimum</span>
        <span class="property-indicator"></span>
        <span class="property-type">string?</span>
    </dt>
    <dd>{{% md %}}{{% /md %}}</dd>

    <dt class="property-required"
            title="Required">
        <span>namespace</span>
        <span class="property-indicator"></span>
        <span class="property-type">string</span>
    </dt>
    <dd>{{% md %}}{{% /md %}}</dd>

    <dt class="property-optional"
            title="Optional">
        <span>operator</span>
        <span class="property-indicator"></span>
        <span class="property-type">string?</span>
    </dt>
    <dd>{{% md %}}{{% /md %}}</dd>

    <dt class="property-optional"
            title="Optional">
        <span>period</span>
        <span class="property-indicator"></span>
        <span class="property-type">number?</span>
    </dt>
    <dd>{{% md %}}{{% /md %}}</dd>

    <dt class="property-required"
            title="Required">
        <span>policy<wbr>Name</span>
        <span class="property-indicator"></span>
        <span class="property-type">string</span>
    </dt>
    <dd>{{% md %}}{{% /md %}}</dd>

    <dt class="property-optional"
            title="Optional">
        <span>source</span>
        <span class="property-indicator"></span>
        <span class="property-type">string?</span>
    </dt>
    <dd>{{% md %}}{{% /md %}}</dd>

    <dt class="property-optional"
            title="Optional">
        <span>statistic</span>
        <span class="property-indicator"></span>
        <span class="property-type">string?</span>
    </dt>
    <dd>{{% md %}}{{% /md %}}</dd>

    <dt class="property-optional"
            title="Optional">
        <span>target</span>
        <span class="property-indicator"></span>
        <span class="property-type">string?</span>
    </dt>
    <dd>{{% md %}}{{% /md %}}</dd>

    <dt class="property-required"
            title="Required">
        <span>threshold</span>
        <span class="property-indicator"></span>
        <span class="property-type">number</span>
    </dt>
    <dd>{{% md %}}{{% /md %}}</dd>

    <dt class="property-required"
            title="Required">
        <span>unit</span>
        <span class="property-indicator"></span>
        <span class="property-type">string</span>
    </dt>
    <dd>{{% md %}}{{% /md %}}</dd>

</dl>
{{% /choosable %}}


{{% choosable language python %}}
<dl class="resources-properties">

    <dt class="property-optional"
            title="Optional">
        <span>action<wbr>Type</span>
        <span class="property-indicator"></span>
        <span class="property-type">str</span>
    </dt>
    <dd>{{% md %}}{{% /md %}}</dd>

    <dt class="property-optional"
            title="Optional">
        <span>adjustment</span>
        <span class="property-indicator"></span>
        <span class="property-type">str</span>
    </dt>
    <dd>{{% md %}}{{% /md %}}</dd>

    <dt class="property-optional"
            title="Optional">
        <span>cooldown</span>
        <span class="property-indicator"></span>
        <span class="property-type">float</span>
    </dt>
    <dd>{{% md %}}{{% /md %}}</dd>

    <dt class="property-optional"
            title="Optional">
        <span>dimensions</span>
        <span class="property-indicator"></span>
        <span class="property-type"><a href="#elastigroupscalinguppolicydimension">List[Elastigroup<wbr>Scaling<wbr>Up<wbr>Policy<wbr>Dimension]</a></span>
    </dt>
    <dd>{{% md %}}{{% /md %}}</dd>

    <dt class="property-optional"
            title="Optional">
        <span>evaluation<wbr>Periods</span>
        <span class="property-indicator"></span>
        <span class="property-type">float</span>
    </dt>
    <dd>{{% md %}}{{% /md %}}</dd>

    <dt class="property-optional"
            title="Optional">
        <span>is<wbr>Enabled</span>
        <span class="property-indicator"></span>
        <span class="property-type">bool</span>
    </dt>
    <dd>{{% md %}}{{% /md %}}</dd>

    <dt class="property-optional"
            title="Optional">
        <span>max<wbr>Target<wbr>Capacity</span>
        <span class="property-indicator"></span>
        <span class="property-type">str</span>
    </dt>
    <dd>{{% md %}}{{% /md %}}</dd>

    <dt class="property-optional"
            title="Optional">
        <span>maximum</span>
        <span class="property-indicator"></span>
        <span class="property-type">str</span>
    </dt>
    <dd>{{% md %}}{{% /md %}}</dd>

    <dt class="property-required"
            title="Required">
        <span>metric<wbr>Name</span>
        <span class="property-indicator"></span>
        <span class="property-type">str</span>
    </dt>
    <dd>{{% md %}}{{% /md %}}</dd>

    <dt class="property-optional"
            title="Optional">
        <span>min<wbr>Target<wbr>Capacity</span>
        <span class="property-indicator"></span>
        <span class="property-type">str</span>
    </dt>
    <dd>{{% md %}}{{% /md %}}</dd>

    <dt class="property-optional"
            title="Optional">
        <span>minimum</span>
        <span class="property-indicator"></span>
        <span class="property-type">str</span>
    </dt>
    <dd>{{% md %}}{{% /md %}}</dd>

    <dt class="property-required"
            title="Required">
        <span>namespace</span>
        <span class="property-indicator"></span>
        <span class="property-type">str</span>
    </dt>
    <dd>{{% md %}}{{% /md %}}</dd>

    <dt class="property-optional"
            title="Optional">
        <span>operator</span>
        <span class="property-indicator"></span>
        <span class="property-type">str</span>
    </dt>
    <dd>{{% md %}}{{% /md %}}</dd>

    <dt class="property-optional"
            title="Optional">
        <span>period</span>
        <span class="property-indicator"></span>
        <span class="property-type">float</span>
    </dt>
    <dd>{{% md %}}{{% /md %}}</dd>

    <dt class="property-required"
            title="Required">
        <span>policy<wbr>Name</span>
        <span class="property-indicator"></span>
        <span class="property-type">str</span>
    </dt>
    <dd>{{% md %}}{{% /md %}}</dd>

    <dt class="property-optional"
            title="Optional">
        <span>source</span>
        <span class="property-indicator"></span>
        <span class="property-type">str</span>
    </dt>
    <dd>{{% md %}}{{% /md %}}</dd>

    <dt class="property-optional"
            title="Optional">
        <span>statistic</span>
        <span class="property-indicator"></span>
        <span class="property-type">str</span>
    </dt>
    <dd>{{% md %}}{{% /md %}}</dd>

    <dt class="property-optional"
            title="Optional">
        <span>target</span>
        <span class="property-indicator"></span>
        <span class="property-type">str</span>
    </dt>
    <dd>{{% md %}}{{% /md %}}</dd>

    <dt class="property-required"
            title="Required">
        <span>threshold</span>
        <span class="property-indicator"></span>
        <span class="property-type">float</span>
    </dt>
    <dd>{{% md %}}{{% /md %}}</dd>

    <dt class="property-required"
            title="Required">
        <span>unit</span>
        <span class="property-indicator"></span>
        <span class="property-type">str</span>
    </dt>
    <dd>{{% md %}}{{% /md %}}</dd>

</dl>
{{% /choosable %}}





<h4>Elastigroup<wbr>Scaling<wbr>Up<wbr>Policy<wbr>Dimension</h4>
{{% choosable language nodejs %}}
> See the <a href="/docs/reference/pkg/nodejs/pulumi/spotinst/types/input/#ElastigroupScalingUpPolicyDimension">input</a> and <a href="/docs/reference/pkg/nodejs/pulumi/spotinst/types/output/#ElastigroupScalingUpPolicyDimension">output</a> API doc for this type.
{{% /choosable %}}

{{% choosable language go %}}
> See the <a href="https://pkg.go.dev/github.com/pulumi/pulumi-spotinst/sdk/go/spotinst/aws?tab=doc#ElastigroupScalingUpPolicyDimensionArgs">input</a> and <a href="https://pkg.go.dev/github.com/pulumi/pulumi-spotinst/sdk/go/spotinst/aws?tab=doc#ElastigroupScalingUpPolicyDimensionOutput">output</a> API doc for this type.
{{% /choosable %}}




{{% choosable language csharp %}}
<dl class="resources-properties">

    <dt class="property-required"
            title="Required">
        <span>Name</span>
        <span class="property-indicator"></span>
        <span class="property-type">string</span>
    </dt>
    <dd>{{% md %}}The group name.
{{% /md %}}</dd>

    <dt class="property-optional"
            title="Optional">
        <span>Value</span>
        <span class="property-indicator"></span>
        <span class="property-type">string?</span>
    </dt>
    <dd>{{% md %}}{{% /md %}}</dd>

</dl>
{{% /choosable %}}


{{% choosable language go %}}
<dl class="resources-properties">

    <dt class="property-required"
            title="Required">
        <span>Name</span>
        <span class="property-indicator"></span>
        <span class="property-type">string</span>
    </dt>
    <dd>{{% md %}}The group name.
{{% /md %}}</dd>

    <dt class="property-optional"
            title="Optional">
        <span>Value</span>
        <span class="property-indicator"></span>
        <span class="property-type">*string</span>
    </dt>
    <dd>{{% md %}}{{% /md %}}</dd>

</dl>
{{% /choosable %}}


{{% choosable language nodejs %}}
<dl class="resources-properties">

    <dt class="property-required"
            title="Required">
        <span>name</span>
        <span class="property-indicator"></span>
        <span class="property-type">string</span>
    </dt>
    <dd>{{% md %}}The group name.
{{% /md %}}</dd>

    <dt class="property-optional"
            title="Optional">
        <span>value</span>
        <span class="property-indicator"></span>
        <span class="property-type">string?</span>
    </dt>
    <dd>{{% md %}}{{% /md %}}</dd>

</dl>
{{% /choosable %}}


{{% choosable language python %}}
<dl class="resources-properties">

    <dt class="property-required"
            title="Required">
        <span>name</span>
        <span class="property-indicator"></span>
        <span class="property-type">str</span>
    </dt>
    <dd>{{% md %}}The group name.
{{% /md %}}</dd>

    <dt class="property-optional"
            title="Optional">
        <span>value</span>
        <span class="property-indicator"></span>
        <span class="property-type">str</span>
    </dt>
    <dd>{{% md %}}{{% /md %}}</dd>

</dl>
{{% /choosable %}}





<h4>Elastigroup<wbr>Scheduled<wbr>Task</h4>
{{% choosable language nodejs %}}
> See the <a href="/docs/reference/pkg/nodejs/pulumi/spotinst/types/input/#ElastigroupScheduledTask">input</a> and <a href="/docs/reference/pkg/nodejs/pulumi/spotinst/types/output/#ElastigroupScheduledTask">output</a> API doc for this type.
{{% /choosable %}}

{{% choosable language go %}}
> See the <a href="https://pkg.go.dev/github.com/pulumi/pulumi-spotinst/sdk/go/spotinst/aws?tab=doc#ElastigroupScheduledTaskArgs">input</a> and <a href="https://pkg.go.dev/github.com/pulumi/pulumi-spotinst/sdk/go/spotinst/aws?tab=doc#ElastigroupScheduledTaskOutput">output</a> API doc for this type.
{{% /choosable %}}




{{% choosable language csharp %}}
<dl class="resources-properties">

    <dt class="property-optional"
            title="Optional">
        <span>Adjustment</span>
        <span class="property-indicator"></span>
        <span class="property-type">string?</span>
    </dt>
    <dd>{{% md %}}{{% /md %}}</dd>

    <dt class="property-optional"
            title="Optional">
        <span>Adjustment<wbr>Percentage</span>
        <span class="property-indicator"></span>
        <span class="property-type">string?</span>
    </dt>
    <dd>{{% md %}}{{% /md %}}</dd>

    <dt class="property-optional"
            title="Optional">
        <span>Batch<wbr>Size<wbr>Percentage</span>
        <span class="property-indicator"></span>
        <span class="property-type">string?</span>
    </dt>
    <dd>{{% md %}}{{% /md %}}</dd>

    <dt class="property-optional"
            title="Optional">
        <span>Cron<wbr>Expression</span>
        <span class="property-indicator"></span>
        <span class="property-type">string?</span>
    </dt>
    <dd>{{% md %}}{{% /md %}}</dd>

    <dt class="property-optional"
            title="Optional">
        <span>Frequency</span>
        <span class="property-indicator"></span>
        <span class="property-type">string?</span>
    </dt>
    <dd>{{% md %}}{{% /md %}}</dd>

    <dt class="property-optional"
            title="Optional">
        <span>Grace<wbr>Period</span>
        <span class="property-indicator"></span>
        <span class="property-type">string?</span>
    </dt>
    <dd>{{% md %}}{{% /md %}}</dd>

    <dt class="property-optional"
            title="Optional">
        <span>Is<wbr>Enabled</span>
        <span class="property-indicator"></span>
        <span class="property-type">bool?</span>
    </dt>
    <dd>{{% md %}}{{% /md %}}</dd>

    <dt class="property-optional"
            title="Optional">
        <span>Max<wbr>Capacity</span>
        <span class="property-indicator"></span>
        <span class="property-type">string?</span>
    </dt>
    <dd>{{% md %}}{{% /md %}}</dd>

    <dt class="property-optional"
            title="Optional">
        <span>Min<wbr>Capacity</span>
        <span class="property-indicator"></span>
        <span class="property-type">string?</span>
    </dt>
    <dd>{{% md %}}{{% /md %}}</dd>

    <dt class="property-optional"
            title="Optional">
        <span>Scale<wbr>Max<wbr>Capacity</span>
        <span class="property-indicator"></span>
        <span class="property-type">string?</span>
    </dt>
    <dd>{{% md %}}{{% /md %}}</dd>

    <dt class="property-optional"
            title="Optional">
        <span>Scale<wbr>Min<wbr>Capacity</span>
        <span class="property-indicator"></span>
        <span class="property-type">string?</span>
    </dt>
    <dd>{{% md %}}{{% /md %}}</dd>

    <dt class="property-optional"
            title="Optional">
        <span>Scale<wbr>Target<wbr>Capacity</span>
        <span class="property-indicator"></span>
        <span class="property-type">string?</span>
    </dt>
    <dd>{{% md %}}{{% /md %}}</dd>

    <dt class="property-optional"
            title="Optional">
        <span>Start<wbr>Time</span>
        <span class="property-indicator"></span>
        <span class="property-type">string?</span>
    </dt>
    <dd>{{% md %}}{{% /md %}}</dd>

    <dt class="property-optional"
            title="Optional">
        <span>Target<wbr>Capacity</span>
        <span class="property-indicator"></span>
        <span class="property-type">string?</span>
    </dt>
    <dd>{{% md %}}{{% /md %}}</dd>

    <dt class="property-required"
            title="Required">
        <span>Task<wbr>Type</span>
        <span class="property-indicator"></span>
        <span class="property-type">string</span>
    </dt>
    <dd>{{% md %}}{{% /md %}}</dd>

</dl>
{{% /choosable %}}


{{% choosable language go %}}
<dl class="resources-properties">

    <dt class="property-optional"
            title="Optional">
        <span>Adjustment</span>
        <span class="property-indicator"></span>
        <span class="property-type">*string</span>
    </dt>
    <dd>{{% md %}}{{% /md %}}</dd>

    <dt class="property-optional"
            title="Optional">
        <span>Adjustment<wbr>Percentage</span>
        <span class="property-indicator"></span>
        <span class="property-type">*string</span>
    </dt>
    <dd>{{% md %}}{{% /md %}}</dd>

    <dt class="property-optional"
            title="Optional">
        <span>Batch<wbr>Size<wbr>Percentage</span>
        <span class="property-indicator"></span>
        <span class="property-type">*string</span>
    </dt>
    <dd>{{% md %}}{{% /md %}}</dd>

    <dt class="property-optional"
            title="Optional">
        <span>Cron<wbr>Expression</span>
        <span class="property-indicator"></span>
        <span class="property-type">*string</span>
    </dt>
    <dd>{{% md %}}{{% /md %}}</dd>

    <dt class="property-optional"
            title="Optional">
        <span>Frequency</span>
        <span class="property-indicator"></span>
        <span class="property-type">*string</span>
    </dt>
    <dd>{{% md %}}{{% /md %}}</dd>

    <dt class="property-optional"
            title="Optional">
        <span>Grace<wbr>Period</span>
        <span class="property-indicator"></span>
        <span class="property-type">*string</span>
    </dt>
    <dd>{{% md %}}{{% /md %}}</dd>

    <dt class="property-optional"
            title="Optional">
        <span>Is<wbr>Enabled</span>
        <span class="property-indicator"></span>
        <span class="property-type">*bool</span>
    </dt>
    <dd>{{% md %}}{{% /md %}}</dd>

    <dt class="property-optional"
            title="Optional">
        <span>Max<wbr>Capacity</span>
        <span class="property-indicator"></span>
        <span class="property-type">*string</span>
    </dt>
    <dd>{{% md %}}{{% /md %}}</dd>

    <dt class="property-optional"
            title="Optional">
        <span>Min<wbr>Capacity</span>
        <span class="property-indicator"></span>
        <span class="property-type">*string</span>
    </dt>
    <dd>{{% md %}}{{% /md %}}</dd>

    <dt class="property-optional"
            title="Optional">
        <span>Scale<wbr>Max<wbr>Capacity</span>
        <span class="property-indicator"></span>
        <span class="property-type">*string</span>
    </dt>
    <dd>{{% md %}}{{% /md %}}</dd>

    <dt class="property-optional"
            title="Optional">
        <span>Scale<wbr>Min<wbr>Capacity</span>
        <span class="property-indicator"></span>
        <span class="property-type">*string</span>
    </dt>
    <dd>{{% md %}}{{% /md %}}</dd>

    <dt class="property-optional"
            title="Optional">
        <span>Scale<wbr>Target<wbr>Capacity</span>
        <span class="property-indicator"></span>
        <span class="property-type">*string</span>
    </dt>
    <dd>{{% md %}}{{% /md %}}</dd>

    <dt class="property-optional"
            title="Optional">
        <span>Start<wbr>Time</span>
        <span class="property-indicator"></span>
        <span class="property-type">*string</span>
    </dt>
    <dd>{{% md %}}{{% /md %}}</dd>

    <dt class="property-optional"
            title="Optional">
        <span>Target<wbr>Capacity</span>
        <span class="property-indicator"></span>
        <span class="property-type">*string</span>
    </dt>
    <dd>{{% md %}}{{% /md %}}</dd>

    <dt class="property-required"
            title="Required">
        <span>Task<wbr>Type</span>
        <span class="property-indicator"></span>
        <span class="property-type">string</span>
    </dt>
    <dd>{{% md %}}{{% /md %}}</dd>

</dl>
{{% /choosable %}}


{{% choosable language nodejs %}}
<dl class="resources-properties">

    <dt class="property-optional"
            title="Optional">
        <span>adjustment</span>
        <span class="property-indicator"></span>
        <span class="property-type">string?</span>
    </dt>
    <dd>{{% md %}}{{% /md %}}</dd>

    <dt class="property-optional"
            title="Optional">
        <span>adjustment<wbr>Percentage</span>
        <span class="property-indicator"></span>
        <span class="property-type">string?</span>
    </dt>
    <dd>{{% md %}}{{% /md %}}</dd>

    <dt class="property-optional"
            title="Optional">
        <span>batch<wbr>Size<wbr>Percentage</span>
        <span class="property-indicator"></span>
        <span class="property-type">string?</span>
    </dt>
    <dd>{{% md %}}{{% /md %}}</dd>

    <dt class="property-optional"
            title="Optional">
        <span>cron<wbr>Expression</span>
        <span class="property-indicator"></span>
        <span class="property-type">string?</span>
    </dt>
    <dd>{{% md %}}{{% /md %}}</dd>

    <dt class="property-optional"
            title="Optional">
        <span>frequency</span>
        <span class="property-indicator"></span>
        <span class="property-type">string?</span>
    </dt>
    <dd>{{% md %}}{{% /md %}}</dd>

    <dt class="property-optional"
            title="Optional">
        <span>grace<wbr>Period</span>
        <span class="property-indicator"></span>
        <span class="property-type">string?</span>
    </dt>
    <dd>{{% md %}}{{% /md %}}</dd>

    <dt class="property-optional"
            title="Optional">
        <span>is<wbr>Enabled</span>
        <span class="property-indicator"></span>
        <span class="property-type">boolean?</span>
    </dt>
    <dd>{{% md %}}{{% /md %}}</dd>

    <dt class="property-optional"
            title="Optional">
        <span>max<wbr>Capacity</span>
        <span class="property-indicator"></span>
        <span class="property-type">string?</span>
    </dt>
    <dd>{{% md %}}{{% /md %}}</dd>

    <dt class="property-optional"
            title="Optional">
        <span>min<wbr>Capacity</span>
        <span class="property-indicator"></span>
        <span class="property-type">string?</span>
    </dt>
    <dd>{{% md %}}{{% /md %}}</dd>

    <dt class="property-optional"
            title="Optional">
        <span>scale<wbr>Max<wbr>Capacity</span>
        <span class="property-indicator"></span>
        <span class="property-type">string?</span>
    </dt>
    <dd>{{% md %}}{{% /md %}}</dd>

    <dt class="property-optional"
            title="Optional">
        <span>scale<wbr>Min<wbr>Capacity</span>
        <span class="property-indicator"></span>
        <span class="property-type">string?</span>
    </dt>
    <dd>{{% md %}}{{% /md %}}</dd>

    <dt class="property-optional"
            title="Optional">
        <span>scale<wbr>Target<wbr>Capacity</span>
        <span class="property-indicator"></span>
        <span class="property-type">string?</span>
    </dt>
    <dd>{{% md %}}{{% /md %}}</dd>

    <dt class="property-optional"
            title="Optional">
        <span>start<wbr>Time</span>
        <span class="property-indicator"></span>
        <span class="property-type">string?</span>
    </dt>
    <dd>{{% md %}}{{% /md %}}</dd>

    <dt class="property-optional"
            title="Optional">
        <span>target<wbr>Capacity</span>
        <span class="property-indicator"></span>
        <span class="property-type">string?</span>
    </dt>
    <dd>{{% md %}}{{% /md %}}</dd>

    <dt class="property-required"
            title="Required">
        <span>task<wbr>Type</span>
        <span class="property-indicator"></span>
        <span class="property-type">string</span>
    </dt>
    <dd>{{% md %}}{{% /md %}}</dd>

</dl>
{{% /choosable %}}


{{% choosable language python %}}
<dl class="resources-properties">

    <dt class="property-optional"
            title="Optional">
        <span>adjustment</span>
        <span class="property-indicator"></span>
        <span class="property-type">str</span>
    </dt>
    <dd>{{% md %}}{{% /md %}}</dd>

    <dt class="property-optional"
            title="Optional">
        <span>adjustment<wbr>Percentage</span>
        <span class="property-indicator"></span>
        <span class="property-type">str</span>
    </dt>
    <dd>{{% md %}}{{% /md %}}</dd>

    <dt class="property-optional"
            title="Optional">
        <span>batch<wbr>Size<wbr>Percentage</span>
        <span class="property-indicator"></span>
        <span class="property-type">str</span>
    </dt>
    <dd>{{% md %}}{{% /md %}}</dd>

    <dt class="property-optional"
            title="Optional">
        <span>cron<wbr>Expression</span>
        <span class="property-indicator"></span>
        <span class="property-type">str</span>
    </dt>
    <dd>{{% md %}}{{% /md %}}</dd>

    <dt class="property-optional"
            title="Optional">
        <span>frequency</span>
        <span class="property-indicator"></span>
        <span class="property-type">str</span>
    </dt>
    <dd>{{% md %}}{{% /md %}}</dd>

    <dt class="property-optional"
            title="Optional">
        <span>grace_<wbr>period</span>
        <span class="property-indicator"></span>
        <span class="property-type">str</span>
    </dt>
    <dd>{{% md %}}{{% /md %}}</dd>

    <dt class="property-optional"
            title="Optional">
        <span>is<wbr>Enabled</span>
        <span class="property-indicator"></span>
        <span class="property-type">bool</span>
    </dt>
    <dd>{{% md %}}{{% /md %}}</dd>

    <dt class="property-optional"
            title="Optional">
        <span>max<wbr>Capacity</span>
        <span class="property-indicator"></span>
        <span class="property-type">str</span>
    </dt>
    <dd>{{% md %}}{{% /md %}}</dd>

    <dt class="property-optional"
            title="Optional">
        <span>min<wbr>Capacity</span>
        <span class="property-indicator"></span>
        <span class="property-type">str</span>
    </dt>
    <dd>{{% md %}}{{% /md %}}</dd>

    <dt class="property-optional"
            title="Optional">
        <span>scale<wbr>Max<wbr>Capacity</span>
        <span class="property-indicator"></span>
        <span class="property-type">str</span>
    </dt>
    <dd>{{% md %}}{{% /md %}}</dd>

    <dt class="property-optional"
            title="Optional">
        <span>scale<wbr>Min<wbr>Capacity</span>
        <span class="property-indicator"></span>
        <span class="property-type">str</span>
    </dt>
    <dd>{{% md %}}{{% /md %}}</dd>

    <dt class="property-optional"
            title="Optional">
        <span>scale<wbr>Target<wbr>Capacity</span>
        <span class="property-indicator"></span>
        <span class="property-type">str</span>
    </dt>
    <dd>{{% md %}}{{% /md %}}</dd>

    <dt class="property-optional"
            title="Optional">
        <span>start<wbr>Time</span>
        <span class="property-indicator"></span>
        <span class="property-type">str</span>
    </dt>
    <dd>{{% md %}}{{% /md %}}</dd>

    <dt class="property-optional"
            title="Optional">
        <span>target<wbr>Capacity</span>
        <span class="property-indicator"></span>
        <span class="property-type">str</span>
    </dt>
    <dd>{{% md %}}{{% /md %}}</dd>

    <dt class="property-required"
            title="Required">
        <span>task<wbr>Type</span>
        <span class="property-indicator"></span>
        <span class="property-type">str</span>
    </dt>
    <dd>{{% md %}}{{% /md %}}</dd>

</dl>
{{% /choosable %}}





<h4>Elastigroup<wbr>Signal</h4>
{{% choosable language nodejs %}}
> See the <a href="/docs/reference/pkg/nodejs/pulumi/spotinst/types/input/#ElastigroupSignal">input</a> and <a href="/docs/reference/pkg/nodejs/pulumi/spotinst/types/output/#ElastigroupSignal">output</a> API doc for this type.
{{% /choosable %}}

{{% choosable language go %}}
> See the <a href="https://pkg.go.dev/github.com/pulumi/pulumi-spotinst/sdk/go/spotinst/aws?tab=doc#ElastigroupSignalArgs">input</a> and <a href="https://pkg.go.dev/github.com/pulumi/pulumi-spotinst/sdk/go/spotinst/aws?tab=doc#ElastigroupSignalOutput">output</a> API doc for this type.
{{% /choosable %}}




{{% choosable language csharp %}}
<dl class="resources-properties">

    <dt class="property-required"
            title="Required">
        <span>Name</span>
        <span class="property-indicator"></span>
        <span class="property-type">string</span>
    </dt>
    <dd>{{% md %}}The group name.
{{% /md %}}</dd>

    <dt class="property-optional"
            title="Optional">
        <span>Timeout</span>
        <span class="property-indicator"></span>
        <span class="property-type">int?</span>
    </dt>
    <dd>{{% md %}}{{% /md %}}</dd>

</dl>
{{% /choosable %}}


{{% choosable language go %}}
<dl class="resources-properties">

    <dt class="property-required"
            title="Required">
        <span>Name</span>
        <span class="property-indicator"></span>
        <span class="property-type">string</span>
    </dt>
    <dd>{{% md %}}The group name.
{{% /md %}}</dd>

    <dt class="property-optional"
            title="Optional">
        <span>Timeout</span>
        <span class="property-indicator"></span>
        <span class="property-type">*int</span>
    </dt>
    <dd>{{% md %}}{{% /md %}}</dd>

</dl>
{{% /choosable %}}


{{% choosable language nodejs %}}
<dl class="resources-properties">

    <dt class="property-required"
            title="Required">
        <span>name</span>
        <span class="property-indicator"></span>
        <span class="property-type">string</span>
    </dt>
    <dd>{{% md %}}The group name.
{{% /md %}}</dd>

    <dt class="property-optional"
            title="Optional">
        <span>timeout</span>
        <span class="property-indicator"></span>
        <span class="property-type">number?</span>
    </dt>
    <dd>{{% md %}}{{% /md %}}</dd>

</dl>
{{% /choosable %}}


{{% choosable language python %}}
<dl class="resources-properties">

    <dt class="property-required"
            title="Required">
        <span>name</span>
        <span class="property-indicator"></span>
        <span class="property-type">str</span>
    </dt>
    <dd>{{% md %}}The group name.
{{% /md %}}</dd>

    <dt class="property-optional"
            title="Optional">
        <span>timeout</span>
        <span class="property-indicator"></span>
        <span class="property-type">float</span>
    </dt>
    <dd>{{% md %}}{{% /md %}}</dd>

</dl>
{{% /choosable %}}





<h4>Elastigroup<wbr>Stateful<wbr>Deallocation</h4>
{{% choosable language nodejs %}}
> See the <a href="/docs/reference/pkg/nodejs/pulumi/spotinst/types/input/#ElastigroupStatefulDeallocation">input</a> and <a href="/docs/reference/pkg/nodejs/pulumi/spotinst/types/output/#ElastigroupStatefulDeallocation">output</a> API doc for this type.
{{% /choosable %}}

{{% choosable language go %}}
> See the <a href="https://pkg.go.dev/github.com/pulumi/pulumi-spotinst/sdk/go/spotinst/aws?tab=doc#ElastigroupStatefulDeallocationArgs">input</a> and <a href="https://pkg.go.dev/github.com/pulumi/pulumi-spotinst/sdk/go/spotinst/aws?tab=doc#ElastigroupStatefulDeallocationOutput">output</a> API doc for this type.
{{% /choosable %}}




{{% choosable language csharp %}}
<dl class="resources-properties">

    <dt class="property-optional"
            title="Optional">
        <span>Should<wbr>Delete<wbr>Images</span>
        <span class="property-indicator"></span>
        <span class="property-type">bool?</span>
    </dt>
    <dd>{{% md %}}{{% /md %}}</dd>

    <dt class="property-optional"
            title="Optional">
        <span>Should<wbr>Delete<wbr>Network<wbr>Interfaces</span>
        <span class="property-indicator"></span>
        <span class="property-type">bool?</span>
    </dt>
    <dd>{{% md %}}{{% /md %}}</dd>

    <dt class="property-optional"
            title="Optional">
        <span>Should<wbr>Delete<wbr>Snapshots</span>
        <span class="property-indicator"></span>
        <span class="property-type">bool?</span>
    </dt>
    <dd>{{% md %}}{{% /md %}}</dd>

    <dt class="property-optional"
            title="Optional">
        <span>Should<wbr>Delete<wbr>Volumes</span>
        <span class="property-indicator"></span>
        <span class="property-type">bool?</span>
    </dt>
    <dd>{{% md %}}{{% /md %}}</dd>

</dl>
{{% /choosable %}}


{{% choosable language go %}}
<dl class="resources-properties">

    <dt class="property-optional"
            title="Optional">
        <span>Should<wbr>Delete<wbr>Images</span>
        <span class="property-indicator"></span>
        <span class="property-type">*bool</span>
    </dt>
    <dd>{{% md %}}{{% /md %}}</dd>

    <dt class="property-optional"
            title="Optional">
        <span>Should<wbr>Delete<wbr>Network<wbr>Interfaces</span>
        <span class="property-indicator"></span>
        <span class="property-type">*bool</span>
    </dt>
    <dd>{{% md %}}{{% /md %}}</dd>

    <dt class="property-optional"
            title="Optional">
        <span>Should<wbr>Delete<wbr>Snapshots</span>
        <span class="property-indicator"></span>
        <span class="property-type">*bool</span>
    </dt>
    <dd>{{% md %}}{{% /md %}}</dd>

    <dt class="property-optional"
            title="Optional">
        <span>Should<wbr>Delete<wbr>Volumes</span>
        <span class="property-indicator"></span>
        <span class="property-type">*bool</span>
    </dt>
    <dd>{{% md %}}{{% /md %}}</dd>

</dl>
{{% /choosable %}}


{{% choosable language nodejs %}}
<dl class="resources-properties">

    <dt class="property-optional"
            title="Optional">
        <span>should<wbr>Delete<wbr>Images</span>
        <span class="property-indicator"></span>
        <span class="property-type">boolean?</span>
    </dt>
    <dd>{{% md %}}{{% /md %}}</dd>

    <dt class="property-optional"
            title="Optional">
        <span>should<wbr>Delete<wbr>Network<wbr>Interfaces</span>
        <span class="property-indicator"></span>
        <span class="property-type">boolean?</span>
    </dt>
    <dd>{{% md %}}{{% /md %}}</dd>

    <dt class="property-optional"
            title="Optional">
        <span>should<wbr>Delete<wbr>Snapshots</span>
        <span class="property-indicator"></span>
        <span class="property-type">boolean?</span>
    </dt>
    <dd>{{% md %}}{{% /md %}}</dd>

    <dt class="property-optional"
            title="Optional">
        <span>should<wbr>Delete<wbr>Volumes</span>
        <span class="property-indicator"></span>
        <span class="property-type">boolean?</span>
    </dt>
    <dd>{{% md %}}{{% /md %}}</dd>

</dl>
{{% /choosable %}}


{{% choosable language python %}}
<dl class="resources-properties">

    <dt class="property-optional"
            title="Optional">
        <span>should<wbr>Delete<wbr>Images</span>
        <span class="property-indicator"></span>
        <span class="property-type">bool</span>
    </dt>
    <dd>{{% md %}}{{% /md %}}</dd>

    <dt class="property-optional"
            title="Optional">
        <span>should<wbr>Delete<wbr>Network<wbr>Interfaces</span>
        <span class="property-indicator"></span>
        <span class="property-type">bool</span>
    </dt>
    <dd>{{% md %}}{{% /md %}}</dd>

    <dt class="property-optional"
            title="Optional">
        <span>should<wbr>Delete<wbr>Snapshots</span>
        <span class="property-indicator"></span>
        <span class="property-type">bool</span>
    </dt>
    <dd>{{% md %}}{{% /md %}}</dd>

    <dt class="property-optional"
            title="Optional">
        <span>should<wbr>Delete<wbr>Volumes</span>
        <span class="property-indicator"></span>
        <span class="property-type">bool</span>
    </dt>
    <dd>{{% md %}}{{% /md %}}</dd>

</dl>
{{% /choosable %}}





<h4>Elastigroup<wbr>Tag</h4>
{{% choosable language nodejs %}}
> See the <a href="/docs/reference/pkg/nodejs/pulumi/spotinst/types/input/#ElastigroupTag">input</a> and <a href="/docs/reference/pkg/nodejs/pulumi/spotinst/types/output/#ElastigroupTag">output</a> API doc for this type.
{{% /choosable %}}

{{% choosable language go %}}
> See the <a href="https://pkg.go.dev/github.com/pulumi/pulumi-spotinst/sdk/go/spotinst/aws?tab=doc#ElastigroupTagArgs">input</a> and <a href="https://pkg.go.dev/github.com/pulumi/pulumi-spotinst/sdk/go/spotinst/aws?tab=doc#ElastigroupTagOutput">output</a> API doc for this type.
{{% /choosable %}}




{{% choosable language csharp %}}
<dl class="resources-properties">

    <dt class="property-optional"
            title="Optional">
        <span>Key</span>
        <span class="property-indicator"></span>
        <span class="property-type">string?</span>
    </dt>
    <dd>{{% md %}}{{% /md %}}</dd>

    <dt class="property-optional"
            title="Optional">
        <span>Value</span>
        <span class="property-indicator"></span>
        <span class="property-type">string?</span>
    </dt>
    <dd>{{% md %}}{{% /md %}}</dd>

</dl>
{{% /choosable %}}


{{% choosable language go %}}
<dl class="resources-properties">

    <dt class="property-optional"
            title="Optional">
        <span>Key</span>
        <span class="property-indicator"></span>
        <span class="property-type">*string</span>
    </dt>
    <dd>{{% md %}}{{% /md %}}</dd>

    <dt class="property-optional"
            title="Optional">
        <span>Value</span>
        <span class="property-indicator"></span>
        <span class="property-type">*string</span>
    </dt>
    <dd>{{% md %}}{{% /md %}}</dd>

</dl>
{{% /choosable %}}


{{% choosable language nodejs %}}
<dl class="resources-properties">

    <dt class="property-optional"
            title="Optional">
        <span>key</span>
        <span class="property-indicator"></span>
        <span class="property-type">string?</span>
    </dt>
    <dd>{{% md %}}{{% /md %}}</dd>

    <dt class="property-optional"
            title="Optional">
        <span>value</span>
        <span class="property-indicator"></span>
        <span class="property-type">string?</span>
    </dt>
    <dd>{{% md %}}{{% /md %}}</dd>

</dl>
{{% /choosable %}}


{{% choosable language python %}}
<dl class="resources-properties">

    <dt class="property-optional"
            title="Optional">
        <span>key</span>
        <span class="property-indicator"></span>
        <span class="property-type">str</span>
    </dt>
    <dd>{{% md %}}{{% /md %}}</dd>

    <dt class="property-optional"
            title="Optional">
        <span>value</span>
        <span class="property-indicator"></span>
        <span class="property-type">str</span>
    </dt>
    <dd>{{% md %}}{{% /md %}}</dd>

</dl>
{{% /choosable %}}





<h4>Elastigroup<wbr>Update<wbr>Policy</h4>
{{% choosable language nodejs %}}
> See the <a href="/docs/reference/pkg/nodejs/pulumi/spotinst/types/input/#ElastigroupUpdatePolicy">input</a> and <a href="/docs/reference/pkg/nodejs/pulumi/spotinst/types/output/#ElastigroupUpdatePolicy">output</a> API doc for this type.
{{% /choosable %}}

{{% choosable language go %}}
> See the <a href="https://pkg.go.dev/github.com/pulumi/pulumi-spotinst/sdk/go/spotinst/aws?tab=doc#ElastigroupUpdatePolicyArgs">input</a> and <a href="https://pkg.go.dev/github.com/pulumi/pulumi-spotinst/sdk/go/spotinst/aws?tab=doc#ElastigroupUpdatePolicyOutput">output</a> API doc for this type.
{{% /choosable %}}




{{% choosable language csharp %}}
<dl class="resources-properties">

    <dt class="property-optional"
            title="Optional">
        <span>Auto<wbr>Apply<wbr>Tags</span>
        <span class="property-indicator"></span>
        <span class="property-type">bool?</span>
    </dt>
    <dd>{{% md %}}{{% /md %}}</dd>

    <dt class="property-optional"
            title="Optional">
        <span>Roll<wbr>Config</span>
        <span class="property-indicator"></span>
        <span class="property-type"><a href="#elastigroupupdatepolicyrollconfig">Elastigroup<wbr>Update<wbr>Policy<wbr>Roll<wbr>Config<wbr>Args?</a></span>
    </dt>
    <dd>{{% md %}}{{% /md %}}</dd>

    <dt class="property-required"
            title="Required">
        <span>Should<wbr>Resume<wbr>Stateful</span>
        <span class="property-indicator"></span>
        <span class="property-type">bool</span>
    </dt>
    <dd>{{% md %}}{{% /md %}}</dd>

    <dt class="property-required"
            title="Required">
        <span>Should<wbr>Roll</span>
        <span class="property-indicator"></span>
        <span class="property-type">bool</span>
    </dt>
    <dd>{{% md %}}{{% /md %}}</dd>

</dl>
{{% /choosable %}}


{{% choosable language go %}}
<dl class="resources-properties">

    <dt class="property-optional"
            title="Optional">
        <span>Auto<wbr>Apply<wbr>Tags</span>
        <span class="property-indicator"></span>
        <span class="property-type">*bool</span>
    </dt>
    <dd>{{% md %}}{{% /md %}}</dd>

    <dt class="property-optional"
            title="Optional">
        <span>Roll<wbr>Config</span>
        <span class="property-indicator"></span>
        <span class="property-type"><a href="#elastigroupupdatepolicyrollconfig">*Elastigroup<wbr>Update<wbr>Policy<wbr>Roll<wbr>Config</a></span>
    </dt>
    <dd>{{% md %}}{{% /md %}}</dd>

    <dt class="property-required"
            title="Required">
        <span>Should<wbr>Resume<wbr>Stateful</span>
        <span class="property-indicator"></span>
        <span class="property-type">bool</span>
    </dt>
    <dd>{{% md %}}{{% /md %}}</dd>

    <dt class="property-required"
            title="Required">
        <span>Should<wbr>Roll</span>
        <span class="property-indicator"></span>
        <span class="property-type">bool</span>
    </dt>
    <dd>{{% md %}}{{% /md %}}</dd>

</dl>
{{% /choosable %}}


{{% choosable language nodejs %}}
<dl class="resources-properties">

    <dt class="property-optional"
            title="Optional">
        <span>auto<wbr>Apply<wbr>Tags</span>
        <span class="property-indicator"></span>
        <span class="property-type">boolean?</span>
    </dt>
    <dd>{{% md %}}{{% /md %}}</dd>

    <dt class="property-optional"
            title="Optional">
        <span>roll<wbr>Config</span>
        <span class="property-indicator"></span>
        <span class="property-type"><a href="#elastigroupupdatepolicyrollconfig">Elastigroup<wbr>Update<wbr>Policy<wbr>Roll<wbr>Config?</a></span>
    </dt>
    <dd>{{% md %}}{{% /md %}}</dd>

    <dt class="property-required"
            title="Required">
        <span>should<wbr>Resume<wbr>Stateful</span>
        <span class="property-indicator"></span>
        <span class="property-type">boolean</span>
    </dt>
    <dd>{{% md %}}{{% /md %}}</dd>

    <dt class="property-required"
            title="Required">
        <span>should<wbr>Roll</span>
        <span class="property-indicator"></span>
        <span class="property-type">boolean</span>
    </dt>
    <dd>{{% md %}}{{% /md %}}</dd>

</dl>
{{% /choosable %}}


{{% choosable language python %}}
<dl class="resources-properties">

    <dt class="property-optional"
            title="Optional">
        <span>auto<wbr>Apply<wbr>Tags</span>
        <span class="property-indicator"></span>
        <span class="property-type">bool</span>
    </dt>
    <dd>{{% md %}}{{% /md %}}</dd>

    <dt class="property-optional"
            title="Optional">
        <span>roll<wbr>Config</span>
        <span class="property-indicator"></span>
        <span class="property-type"><a href="#elastigroupupdatepolicyrollconfig">Dict[Elastigroup<wbr>Update<wbr>Policy<wbr>Roll<wbr>Config]</a></span>
    </dt>
    <dd>{{% md %}}{{% /md %}}</dd>

    <dt class="property-required"
            title="Required">
        <span>should<wbr>Resume<wbr>Stateful</span>
        <span class="property-indicator"></span>
        <span class="property-type">bool</span>
    </dt>
    <dd>{{% md %}}{{% /md %}}</dd>

    <dt class="property-required"
            title="Required">
        <span>should<wbr>Roll</span>
        <span class="property-indicator"></span>
        <span class="property-type">bool</span>
    </dt>
    <dd>{{% md %}}{{% /md %}}</dd>

</dl>
{{% /choosable %}}





<h4>Elastigroup<wbr>Update<wbr>Policy<wbr>Roll<wbr>Config</h4>
{{% choosable language nodejs %}}
> See the <a href="/docs/reference/pkg/nodejs/pulumi/spotinst/types/input/#ElastigroupUpdatePolicyRollConfig">input</a> and <a href="/docs/reference/pkg/nodejs/pulumi/spotinst/types/output/#ElastigroupUpdatePolicyRollConfig">output</a> API doc for this type.
{{% /choosable %}}

{{% choosable language go %}}
> See the <a href="https://pkg.go.dev/github.com/pulumi/pulumi-spotinst/sdk/go/spotinst/aws?tab=doc#ElastigroupUpdatePolicyRollConfigArgs">input</a> and <a href="https://pkg.go.dev/github.com/pulumi/pulumi-spotinst/sdk/go/spotinst/aws?tab=doc#ElastigroupUpdatePolicyRollConfigOutput">output</a> API doc for this type.
{{% /choosable %}}




{{% choosable language csharp %}}
<dl class="resources-properties">

    <dt class="property-required"
            title="Required">
        <span>Batch<wbr>Size<wbr>Percentage</span>
        <span class="property-indicator"></span>
        <span class="property-type">int</span>
    </dt>
    <dd>{{% md %}}{{% /md %}}</dd>

    <dt class="property-optional"
            title="Optional">
        <span>Grace<wbr>Period</span>
        <span class="property-indicator"></span>
        <span class="property-type">int?</span>
    </dt>
    <dd>{{% md %}}{{% /md %}}</dd>

    <dt class="property-optional"
            title="Optional">
        <span>Health<wbr>Check<wbr>Type</span>
        <span class="property-indicator"></span>
        <span class="property-type">string?</span>
    </dt>
    <dd>{{% md %}}The service that will perform health checks for the instance. Valid values: `"ELB"`, `"HCS"`, `"TARGET_GROUP"`, `"MLB"`, `"EC2"`, `"MULTAI_TARGET_SET"`, `"MLB_RUNTIME"`, `"K8S_NODE"`, `"NOMAD_NODE"`, `"ECS_CLUSTER_INSTANCE"`.
{{% /md %}}</dd>

    <dt class="property-optional"
            title="Optional">
        <span>Strategy</span>
        <span class="property-indicator"></span>
        <span class="property-type"><a href="#elastigroupupdatepolicyrollconfigstrategy">Elastigroup<wbr>Update<wbr>Policy<wbr>Roll<wbr>Config<wbr>Strategy<wbr>Args?</a></span>
    </dt>
    <dd>{{% md %}}{{% /md %}}</dd>

    <dt class="property-optional"
            title="Optional">
        <span>Wait<wbr>For<wbr>Roll<wbr>Percentage</span>
        <span class="property-indicator"></span>
        <span class="property-type">int?</span>
    </dt>
    <dd>{{% md %}}{{% /md %}}</dd>

    <dt class="property-optional"
            title="Optional">
        <span>Wait<wbr>For<wbr>Roll<wbr>Timeout</span>
        <span class="property-indicator"></span>
        <span class="property-type">int?</span>
    </dt>
    <dd>{{% md %}}{{% /md %}}</dd>

</dl>
{{% /choosable %}}


{{% choosable language go %}}
<dl class="resources-properties">

    <dt class="property-required"
            title="Required">
        <span>Batch<wbr>Size<wbr>Percentage</span>
        <span class="property-indicator"></span>
        <span class="property-type">int</span>
    </dt>
    <dd>{{% md %}}{{% /md %}}</dd>

    <dt class="property-optional"
            title="Optional">
        <span>Grace<wbr>Period</span>
        <span class="property-indicator"></span>
        <span class="property-type">*int</span>
    </dt>
    <dd>{{% md %}}{{% /md %}}</dd>

    <dt class="property-optional"
            title="Optional">
        <span>Health<wbr>Check<wbr>Type</span>
        <span class="property-indicator"></span>
        <span class="property-type">*string</span>
    </dt>
    <dd>{{% md %}}The service that will perform health checks for the instance. Valid values: `"ELB"`, `"HCS"`, `"TARGET_GROUP"`, `"MLB"`, `"EC2"`, `"MULTAI_TARGET_SET"`, `"MLB_RUNTIME"`, `"K8S_NODE"`, `"NOMAD_NODE"`, `"ECS_CLUSTER_INSTANCE"`.
{{% /md %}}</dd>

    <dt class="property-optional"
            title="Optional">
        <span>Strategy</span>
        <span class="property-indicator"></span>
        <span class="property-type"><a href="#elastigroupupdatepolicyrollconfigstrategy">*Elastigroup<wbr>Update<wbr>Policy<wbr>Roll<wbr>Config<wbr>Strategy</a></span>
    </dt>
    <dd>{{% md %}}{{% /md %}}</dd>

    <dt class="property-optional"
            title="Optional">
        <span>Wait<wbr>For<wbr>Roll<wbr>Percentage</span>
        <span class="property-indicator"></span>
        <span class="property-type">*int</span>
    </dt>
    <dd>{{% md %}}{{% /md %}}</dd>

    <dt class="property-optional"
            title="Optional">
        <span>Wait<wbr>For<wbr>Roll<wbr>Timeout</span>
        <span class="property-indicator"></span>
        <span class="property-type">*int</span>
    </dt>
    <dd>{{% md %}}{{% /md %}}</dd>

</dl>
{{% /choosable %}}


{{% choosable language nodejs %}}
<dl class="resources-properties">

    <dt class="property-required"
            title="Required">
        <span>batch<wbr>Size<wbr>Percentage</span>
        <span class="property-indicator"></span>
        <span class="property-type">number</span>
    </dt>
    <dd>{{% md %}}{{% /md %}}</dd>

    <dt class="property-optional"
            title="Optional">
        <span>grace<wbr>Period</span>
        <span class="property-indicator"></span>
        <span class="property-type">number?</span>
    </dt>
    <dd>{{% md %}}{{% /md %}}</dd>

    <dt class="property-optional"
            title="Optional">
        <span>health<wbr>Check<wbr>Type</span>
        <span class="property-indicator"></span>
        <span class="property-type">string?</span>
    </dt>
    <dd>{{% md %}}The service that will perform health checks for the instance. Valid values: `"ELB"`, `"HCS"`, `"TARGET_GROUP"`, `"MLB"`, `"EC2"`, `"MULTAI_TARGET_SET"`, `"MLB_RUNTIME"`, `"K8S_NODE"`, `"NOMAD_NODE"`, `"ECS_CLUSTER_INSTANCE"`.
{{% /md %}}</dd>

    <dt class="property-optional"
            title="Optional">
        <span>strategy</span>
        <span class="property-indicator"></span>
        <span class="property-type"><a href="#elastigroupupdatepolicyrollconfigstrategy">Elastigroup<wbr>Update<wbr>Policy<wbr>Roll<wbr>Config<wbr>Strategy?</a></span>
    </dt>
    <dd>{{% md %}}{{% /md %}}</dd>

    <dt class="property-optional"
            title="Optional">
        <span>wait<wbr>For<wbr>Roll<wbr>Percentage</span>
        <span class="property-indicator"></span>
        <span class="property-type">number?</span>
    </dt>
    <dd>{{% md %}}{{% /md %}}</dd>

    <dt class="property-optional"
            title="Optional">
        <span>wait<wbr>For<wbr>Roll<wbr>Timeout</span>
        <span class="property-indicator"></span>
        <span class="property-type">number?</span>
    </dt>
    <dd>{{% md %}}{{% /md %}}</dd>

</dl>
{{% /choosable %}}


{{% choosable language python %}}
<dl class="resources-properties">

    <dt class="property-required"
            title="Required">
        <span>batch<wbr>Size<wbr>Percentage</span>
        <span class="property-indicator"></span>
        <span class="property-type">float</span>
    </dt>
    <dd>{{% md %}}{{% /md %}}</dd>

    <dt class="property-optional"
            title="Optional">
        <span>grace_<wbr>period</span>
        <span class="property-indicator"></span>
        <span class="property-type">float</span>
    </dt>
    <dd>{{% md %}}{{% /md %}}</dd>

    <dt class="property-optional"
            title="Optional">
        <span>health_<wbr>check_<wbr>type</span>
        <span class="property-indicator"></span>
        <span class="property-type">str</span>
    </dt>
    <dd>{{% md %}}The service that will perform health checks for the instance. Valid values: `"ELB"`, `"HCS"`, `"TARGET_GROUP"`, `"MLB"`, `"EC2"`, `"MULTAI_TARGET_SET"`, `"MLB_RUNTIME"`, `"K8S_NODE"`, `"NOMAD_NODE"`, `"ECS_CLUSTER_INSTANCE"`.
{{% /md %}}</dd>

    <dt class="property-optional"
            title="Optional">
        <span>strategy</span>
        <span class="property-indicator"></span>
        <span class="property-type"><a href="#elastigroupupdatepolicyrollconfigstrategy">Dict[Elastigroup<wbr>Update<wbr>Policy<wbr>Roll<wbr>Config<wbr>Strategy]</a></span>
    </dt>
    <dd>{{% md %}}{{% /md %}}</dd>

    <dt class="property-optional"
            title="Optional">
        <span>wait<wbr>For<wbr>Roll<wbr>Percentage</span>
        <span class="property-indicator"></span>
        <span class="property-type">float</span>
    </dt>
    <dd>{{% md %}}{{% /md %}}</dd>

    <dt class="property-optional"
            title="Optional">
        <span>wait<wbr>For<wbr>Roll<wbr>Timeout</span>
        <span class="property-indicator"></span>
        <span class="property-type">float</span>
    </dt>
    <dd>{{% md %}}{{% /md %}}</dd>

</dl>
{{% /choosable %}}





<h4>Elastigroup<wbr>Update<wbr>Policy<wbr>Roll<wbr>Config<wbr>Strategy</h4>
{{% choosable language nodejs %}}
> See the <a href="/docs/reference/pkg/nodejs/pulumi/spotinst/types/input/#ElastigroupUpdatePolicyRollConfigStrategy">input</a> and <a href="/docs/reference/pkg/nodejs/pulumi/spotinst/types/output/#ElastigroupUpdatePolicyRollConfigStrategy">output</a> API doc for this type.
{{% /choosable %}}

{{% choosable language go %}}
> See the <a href="https://pkg.go.dev/github.com/pulumi/pulumi-spotinst/sdk/go/spotinst/aws?tab=doc#ElastigroupUpdatePolicyRollConfigStrategyArgs">input</a> and <a href="https://pkg.go.dev/github.com/pulumi/pulumi-spotinst/sdk/go/spotinst/aws?tab=doc#ElastigroupUpdatePolicyRollConfigStrategyOutput">output</a> API doc for this type.
{{% /choosable %}}




{{% choosable language csharp %}}
<dl class="resources-properties">

    <dt class="property-required"
            title="Required">
        <span>Action</span>
        <span class="property-indicator"></span>
        <span class="property-type">string</span>
    </dt>
    <dd>{{% md %}}{{% /md %}}</dd>

    <dt class="property-optional"
            title="Optional">
        <span>Batch<wbr>Min<wbr>Healthy<wbr>Percentage</span>
        <span class="property-indicator"></span>
        <span class="property-type">int?</span>
    </dt>
    <dd>{{% md %}}{{% /md %}}</dd>

    <dt class="property-optional"
            title="Optional">
        <span>Should<wbr>Drain<wbr>Instances</span>
        <span class="property-indicator"></span>
        <span class="property-type">bool?</span>
    </dt>
    <dd>{{% md %}}{{% /md %}}</dd>

</dl>
{{% /choosable %}}


{{% choosable language go %}}
<dl class="resources-properties">

    <dt class="property-required"
            title="Required">
        <span>Action</span>
        <span class="property-indicator"></span>
        <span class="property-type">string</span>
    </dt>
    <dd>{{% md %}}{{% /md %}}</dd>

    <dt class="property-optional"
            title="Optional">
        <span>Batch<wbr>Min<wbr>Healthy<wbr>Percentage</span>
        <span class="property-indicator"></span>
        <span class="property-type">*int</span>
    </dt>
    <dd>{{% md %}}{{% /md %}}</dd>

    <dt class="property-optional"
            title="Optional">
        <span>Should<wbr>Drain<wbr>Instances</span>
        <span class="property-indicator"></span>
        <span class="property-type">*bool</span>
    </dt>
    <dd>{{% md %}}{{% /md %}}</dd>

</dl>
{{% /choosable %}}


{{% choosable language nodejs %}}
<dl class="resources-properties">

    <dt class="property-required"
            title="Required">
        <span>action</span>
        <span class="property-indicator"></span>
        <span class="property-type">string</span>
    </dt>
    <dd>{{% md %}}{{% /md %}}</dd>

    <dt class="property-optional"
            title="Optional">
        <span>batch<wbr>Min<wbr>Healthy<wbr>Percentage</span>
        <span class="property-indicator"></span>
        <span class="property-type">number?</span>
    </dt>
    <dd>{{% md %}}{{% /md %}}</dd>

    <dt class="property-optional"
            title="Optional">
        <span>should<wbr>Drain<wbr>Instances</span>
        <span class="property-indicator"></span>
        <span class="property-type">boolean?</span>
    </dt>
    <dd>{{% md %}}{{% /md %}}</dd>

</dl>
{{% /choosable %}}


{{% choosable language python %}}
<dl class="resources-properties">

    <dt class="property-required"
            title="Required">
        <span>action</span>
        <span class="property-indicator"></span>
        <span class="property-type">str</span>
    </dt>
    <dd>{{% md %}}{{% /md %}}</dd>

    <dt class="property-optional"
            title="Optional">
        <span>batch<wbr>Min<wbr>Healthy<wbr>Percentage</span>
        <span class="property-indicator"></span>
        <span class="property-type">float</span>
    </dt>
    <dd>{{% md %}}{{% /md %}}</dd>

    <dt class="property-optional"
            title="Optional">
        <span>should<wbr>Drain<wbr>Instances</span>
        <span class="property-indicator"></span>
        <span class="property-type">bool</span>
    </dt>
    <dd>{{% md %}}{{% /md %}}</dd>

</dl>
{{% /choosable %}}









<h3>Package Details</h3>
<dl class="package-details">
	<dt>Repository</dt>
	<dd><a href="https://github.com/pulumi/pulumi-spotinst">https://github.com/pulumi/pulumi-spotinst</a></dd>
	<dt>License</dt>
	<dd>Apache-2.0</dd>
    
</dl>
